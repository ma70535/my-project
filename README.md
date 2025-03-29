# my-project
GitHub初体验
def is_all_odd(n):
    return all(int(c) % 2 != 0 for c in str(n))

result = [str(year) for year in range(1000, 3001) if is_all_odd(year)]
print('@'.join(result))
