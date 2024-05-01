def calculate_inflation(initial_price, final_price):
    inflation_rate = ((final_price - initial_price) / initial_price) * 100
    return inflation_rate

# Example usage
if __name__ == "__main__":
    initial_price = 100  # Initial price of the item
    final_price = 120    # Final price of the item

    inflation_rate = calculate_inflation(initial_price, final_price)
    print(f"The inflation rate is: {inflation_rate}%")
