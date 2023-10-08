import csv
import matplotlib.pyplot as plt

country_counts = {}
with open('data2.cvs', mode='r', newline='') as file:
    csv_reader = csv.reader(file)
    next(csv_reader)  # Skip the header row if it exists
    for row in csv_reader:
        country_name = row[1].strip()  # Assuming country name is in the second column (index 1)
        try:
            count = int(row[2])  # Assuming 'Count' is in the third column (index 2)
            if country_name in country_counts:
                country_counts[country_name] += count
            else:
                country_counts[country_name] = count
        except ValueError:
            # Handle rows with non-integer values in the 'Count' column
            pass

country_names = list(country_counts.keys())
count_sums = list(country_counts.values())


plt.figure(figsize=(10, 6))  # Set the figure size
plt.pie(count_sums, labels=country_names, autopct='%1.1f%%', startangle=140)
plt.axis('equal')  # Equal aspect ratio ensures that pie is drawn as a circle.


plt.title('Permanent Resident - Country of Citizenship')


plt.show()
