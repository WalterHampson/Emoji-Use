📊 Emoji-Use
Description
Emoji-Use is a Python-based project that analyzes emoji usage and visualizes the most popular emojis with context in a horizontal bar graph. The project leverages Matplotlib for plotting and ensures emoji rendering using the Segoe UI Emoji font.

This project reads from a dataset containing emoji usage, counts, and context, and outputs:

A formatted table showing the most popular emojis, their usage counts, and the contexts in which they were used.
A visually appealing horizontal bar chart with a custom purple border that highlights the frequency of emoji usage, restricted to a specific count range.
Features
🏆 Top Emoji Analysis: Extracts the top N most frequently used emojis from the dataset.
📈 Visualization: Displays the results in a bar chart, complete with annotations for usage context.
🎨 Custom Styling: Focused count range for the graph and a vibrant purple border around the plot.
✨ Emoji Rendering: Proper rendering of emojis within the graph using the Segoe UI Emoji font for maximum compatibility.
Requirements
Ensure you have the following installed:

Python 3.x
Matplotlib: For plotting the bar chart.
Pandas: For handling and analyzing the emoji dataset.
Emoji: For rendering and manipulating emoji text.
Pillow (PIL): To handle emoji images if needed.
You can install the dependencies by running:

bash
Copy code
pip install matplotlib pandas emoji pillow
Usage
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/Emoji-Use.git
Prepare your emoji usage dataset in CSV format with at least the following columns:

Emoji: The emoji used.
Count: The frequency of the emoji.
Context: The context or meaning of the emoji use.
Update the file path in the script to point to your CSV file:

python
Copy code
file_path = 'emoji_usage_dataset.csv'
Run the script to display the most popular emojis and generate the plot:

bash
Copy code
python EmojiUse.py
The plot will show the top emojis with a focus on counts between 150 and 225, complete with a stylish purple border.

License
This project is licensed under the MIT License - see the LICENSE file for details.