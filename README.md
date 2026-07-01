def count_unique_numbers(numbers):
    return len(set(numbers))

if __name__ == "__main__":
    nums = [1, 2, 2, 3, 4, 4, 5, 6]
    print(f"Numbers: {nums}")
    print(f"Unique count: {count_unique_numbers(nums)}")
