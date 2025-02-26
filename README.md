Download link :https://programming.engineering/product/homework-3-advanced-design-techniques/

# Homework-3-Advanced-Design-Techniques
Homework 3: Advanced Design Techniques
Problem 1: Task Selection 25 points

Consider a total of n jobs. Let the ith job be designated with a start time si, a finish time fi and a net value vi. Two jobs are said to be compatible if they do not overlap in time. Your goal is to find the subset of mutually compatible jobs that have the maximum total value. Present the following four stages of your design approach to this problem:

Model the above problem as a multi-stage decision problem, identify the state and decision variables, define the state transitions and derive the Bellman equation.

Using the Bellman equation, write a pseudocode to compute the optimal solution using dy-namic programming approach.

Write down the pseudocode for the greedy solution to this problem.

Implement in Python, both the dynamic programming and greedy solutions to this problem and compare the value of the solutions returned for random inputs when there are a total of n = 10 jobs.

Part 3: Advanced Design Techniques

5

TODO: Function to encode the input string using huffman_tree()

Suggestion: Label left children with ’0’ and right children with ’1’

“””

pass

def huffman_decoder(binary_string, tree_root_node):

“””

TODO: Function to decode a binary sequence constructed using huffman_encoder()

“””

pass

if __name__ == ’__main__’:

benchmark_string = ’AABCACAAABCBABBAABAAAACACBBABCBABBACB’ root = huffman_tree(benchmark_string) test_string = ’ABCAAB’

encoded_sequence = huffman_encoder(test_string, root)

decoded_sequence = huffman_decoder(encoded_sequence, root)

print(f”Input:{test_string}”)

print(f”Decoded Sequence:{decoded_sequence}”)

print(“TEST:PASS” if test_string == decoded_sequence else “TEST:FAIL”)
