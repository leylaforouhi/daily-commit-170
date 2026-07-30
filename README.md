def count_letters(text):
    return sum(1 for char in text if char.isalpha())


if __name__ == "__main__":
    sentence = "GitHub Daily Commit #170"

    print(f"Text: {sentence}")
    print(f"Letter count: {count_letters(sentence)}")
