# Python-Program-to-Remove-Specific-Characters-from-a-String-35-100
def strip_chars(string, chars):
    return "".join(c for c in string if c not in chars)

print("\nOriginal String:")
original = "The quick brown fox jumps over the lazy dog."
print(original)

print("After stripping a, e, i, o, u:")
print(strip_chars(original, "aeiou"))
print()

Original String:
The quick brown fox jumps over the lazy dog.
After stripping a, e, i, o, u:
Th qck brwn fx jmps vr th lzy dg.

