# 3A-GONZGA-MP2

Propositional Logic Operations in Python
1. AND Operation (Logical Conjunction)
The AND operation returns True if both operands are True, otherwise it returns False.
python
def and_operation(p, q):
    return p and q

2. OR Operation (Logical Disjunction)
The OR operation returns True if at least one of the operands is True. It only returns False if both operands are False.
python
def or_operation(p, q):
    return p or q

3. NOT Operation (Logical Negation)
The NOT operation inverts the truth value of its operand. If the operand is True, it returns False, and vice versa.
python
def not_operation(p):
    return not p

4. IMPLIES Operation (Logical Implication)
The IMPLIES operation returns False only if the first operand is True and the second operand is False. In all other cases, it returns True.
python
def implies_operation(p, q):
    return not p or q

Example Usage
Here’s how you can use these functions:
python
# Example values
p = True
q = False

# Performing operations
print("AND Operation (p ∧ q):", and_operation(p, q))          # Output: False
print("OR Operation (p ∨ q):", or_operation(p, q))            # Output: True
print("NOT Operation (¬p):", not_operation(p))                # Output: False
print("IMPLIES Operation (p → q):", implies_operation(p, q))  # Output: False

Summary
These functions provide a straightforward implementation of basic propositional logic operations in Python. You can easily extend or modify them for more complex logical expressions as needed. Enjoy experimenting with logical operations!
