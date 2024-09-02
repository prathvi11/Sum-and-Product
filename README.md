# Sum-and-Product
#Write a function that calculates the sum and product of all elements in a tuple of numbers


def sum_product(input_tuple):
    
    sum_result = 0
    product_result = 1
    
    for i in input_tuple:
        sum_result = sum_result+i
        
        product_result = product_result * i
        
    return sum_result , product_result
    
    
    

