```python
def main():
	print("Mab libs where libs get mad.")
	print("Start below:\n")

	number = input("Enter a number from 1 to 12: ")
	noun = input("Enter a noun (plural): ")
	name = input("Enter a name: ")
	sentence = input("Enter any sentence: ")
	verb = input("Enter a verb: ")

	print("\nThe story goes...\n")
	print(f"It was {number} o'clock when I heard a knock at the door.")
	print(f'I opened the door and there was a box full of {noun} with a note saying "From Mr. {name.title()}"')
	print(f'Just as I closed the door I heard a scream "{sentence.upper()}"')
	print(f"I froze in place and all I could do was {verb}.")


if __name__ == '__main__':
	main()
```
