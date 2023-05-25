paragraph = [
    "The quick brown fox",
    "jumps over the lazy dog.",
    "The dog barks,",
    "and the fox runs away."
]

def word_frequency(paragraph):
    result = {}
    words_list = []
    for string in paragraph:
        new_strings = string.replace(".", "").replace(",", "").lower().split()
        words_list.extend(new_strings)
    for word in words_list:
        result[word] = result.get(word, 0) + 1
    return result


frequency = word_frequency(paragraph)
print(frequency)
