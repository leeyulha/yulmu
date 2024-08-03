# yulmu

file_path = '/mnt/data/gercon.txt'

with open(file_path, 'r', encoding='utf-8') as file:
    content = file.read()

# Remove newlines
single_line_content = content.replace('\n', ' ')

# Save the modified content to a new file
output_path = '/mnt/data/gercon_single_line.txt'
with open(output_path, 'w', encoding='utf-8') as file:
    file.write(single_line_content)

output_path
