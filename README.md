def count_lines(content):
    print("No of lines: #")
with open(r"E:/moni/testfile2.txt", 'r')as fp:
    lines = sum(1 for line in fp)
print('total number of lines:',lines)
file = open("E:/moni/testfile2.txt", "r")
content=file.read()
