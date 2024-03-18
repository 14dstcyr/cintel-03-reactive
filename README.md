# cintel-03-reactive

## Additional Python Notes
# ------------------------

## Capitalization matters in Python. Python is case-sensitive: min and Min are different.
## Spelling matters in Python. You must match the spelling of functions and variables exactly.
## Indentation matters in Python. Indentation is used to define code blocks and must be consistent.

# Functions
# ---------
- Functions are used to group code together and make it more readable and reusable.
- We define custom functions that can be called later in the code.
- Functions are blocks of logic that can take inputs, perform work, and return outputs.

# Defining Functions
# ------------------
- Define a function using the def keyword, followed by the function name, parentheses, and a colon. 
- The function name should describe what the function does.
- In the parentheses, specify the inputs needed as arguments the function takes.

-- For example:
---   The function filtered_data() takes no arguments.
---   The function between(min, max) takes two arguments, a minimum and maximum value.
---   Arguments can be positional or keyword arguments, labeled with a parameter name.

## The function body is indented (consistently!) after the colon. 
## Use the return keyword to return a value from a function.

# Calling Functions
# -----------------
- Call a function by using its name followed by parentheses and any required arguments.
    
# Decorators
# ----------
- Use the @ symbol to decorate a function with a decorator.
- Decorators a concise way of calling a function on a function.
- We don't typically write decorators, but we often use them.



https://shinylive.io/py/editor/#code=NobwRAdghgtgpmAXGKAHVA6VBPMAaMAYwHsIAXOcpMASxlWICcyACVAG2LPewzgA9UjOAGcRLKONT8AOhABmjYjBYiAFjQi8BQ0eLoNmLTagCuZPC1M05i5ao1aA7jQAmAczhl99Jq2EQrnCMAPocXDxyBn5sUOzwjKiU7tYQ4iwAxCwAKhpSUIQA1lCebEoAbm6iLGRqcCwACnEJjcmp4q5QZJJeUb5GqFCBkhJSrn2GrCJwUABGTBCjqmm2SirqmtjG-f4zhGQ05XCWAUGMJ3AAjnJyWQCq0zV1LLPW7GQAtJos8qYQ+zRSDViCxOFBXE96k14sFWhAUpoOl0emQMHIkvD2iFXPIWABeWIwxJtREYMGuMIktIACgAlDcIFkAHKwerEXENJQAKzg+0aJTgcmsWAFIWIqG81IO3DgeJkYAAymQQgBhbCMOEIxYAEWR8ss8ho7HYc3YsoAYnFpvSILcWABBVwQqCqKqzKCMOQuWpWGgYERuj3U8WUOVgEO2sC0xAsFhyWOx+MJ4VqABM1PlCsDnqjDITmRYD3qwpM5hC0zNAIAXnA6cCWIRhF16i7XEpUK5iE5FqXWGQQYQ1MRiI8XSR2KYYLbFsm-b3y3BKwcaxmZ-nE4rF7yKBT7WQyIwaK8KPqk+u42AAEJG9gsAAyyR93wAsje6F5giJT2v18B5bMbxCM14VqEIYBgfULwA41sTgCU1DAiD8AveR2BodBgiAx8EPAyD-2IVxsDAyQRBCdx5QAXTwM8WBtfMaPuR4SwgMxlQgSdghoQg637BsmwoCQWHYhIuOMFjzB+JhISEydZlhdlGk4bgtjyft3EYWAXkRGjmNYkJhM47j5XCZSQgAiAQhIP4yDwsAmVk+SOSUngWGvFZkNTAAGG0GMLJi53E5URDQs4eIHfiW1UELYV7SSNVqephLkjUFIVGZ5kYRZzK-H9dLLYKqkYDMwGmOYFjMzRLOIazbLclgVWq8hIIARksZrPM8ywvJ8n9GOLAK9MHXlCnmfgyKUUxUDCviZgEsc6iKUaWHU6rUDE1j60Nd5YQS1QkkIGhRB0gayyGxbiDGlbJuKittzgCkRH2w7SLQkQbOQ+UGipFgFSeo7kJYP8wEdRdDtsgBxSh+2IWyVUcN6NNQSjLFu-Z7rxIG4cRA80GRmj800NCIFlbJGFMY4aJ6-M+t9DA1CK2l63BZ0WCHQ8q1IbpbzJs1612gMgndT1cr9em6Ro3yi1pqBpuZwS1GwJJGCJwo+eeAW4CF46MBl+VwZoWpTFmSD6bgeQwzUfdUBERAAHpbfcA21CNjASBgW3moAFlcN7CHVW2DvIRcPk81MPk6bpIO6RhPDIMNZhNCBCnlOiEwlxl6oimpTWqIYIRMjoaEek1sE0dwJGNFgI6gW4sl1bochziRAhYcHD3GCBvTUWmS+q5Vx0nGlo0TH8u9pwgPVcalfhgkRGzgUNLXYa0YzjH98xTdNPqpcRshzlPzxHw+WAAAVOYIMGrkJFFZfGEyCDkd5CPeE9raM7+P2NhDIUxMpYc-GAYHrlAF+ZpqQYi1KRHEqdP6fxomPYUE9GBTxnuwcs89F5WjgO-des46ZbzAF9TEiJW7txTh-Nex8z6UDOJfZE18NLwAoQ-f+NDMJEK1CENubg6SIAofmb+v9FgAKAcibhU8IFYmgQyLIKos4AAki5qUYeIPOP0J77mCCZBkCC-S91OsQCcU4RDUnHCEFwrhagiDxNSAArJYWxtIcH5l0a7Se09TCzwwRAPEpNybOMPimT2xUOGpBYIot6xB1KwHIdOKhACwjOWwMws2bAkkhFUlExhvD+EJkEX-aQdMlFZNgOAp+OJLD8DDI9Xkz1ILjiYNUv6X5czTi9E7HuUBsB9yqkYmkZiLFWJsfYlgjiAmxlcUglBni0Fz2EKGPx2C+G4NjIgyeGSZihUzOlBY4TinRKQjA9c1DAgXxMtSOIcdtllT-hE5RMTWnHxYaVDKFlMkHJySs9cqkTL4mWCIIpb1znVzxJIxE2J5CVPjgRIiMASJkUgtlPEvZ-Q7MyhVCyVlyB0iOcfH5SlUXKmlGA7exD3K4sPvirghKQj8BNHJdgxVnwkVibA2MVLUTTGVNgeli5ioNRqo8tl+TFgcoZLXRSEQtgKg0RQRISl2k+mFPo-uhjB4mIGW4IZdiHFOOWS4jpazkEeK8fMnxizxnriNRSOo4JgghKSeorocrtFCvPCcs4iSpUpNxCZHg6DnVaKUp8tlrCf4FP4P6WV9qwVpAhVC-8gFgLuFArhfAuTQ35mwNCwixExAIvTV8zN64GmMCabU-61Ei3FoTMS2UpKtROs0fKrg34a1st5cvPEIBE0wWTampCMZ5TXkrg+EC3c01VvbdOqCMK82kXIkgC8l4YUsGZWIZa8oAC+U6Z2HwDDWYiVSvJ4B6naD4F7L1XuvTe29d770Po+HaAASnsA4RwGxxEIJ4rogI0jNwhGbeQ24cpZEfeBiDkGb0yIdE6QSTYAQfonuwb9JoDhAl4ltOV0lq52kvFsIIJANIHHhNJX4-x0OLDHtQgo77jgsCcPUCeixTCPF2uRgEGGQRYZ2s8XDGdcj1A45RhjN4XhMbiGaCETg6jEyOBqIY60JLCb-eIVj916yeGJsR+otQugsD7htQcQxPAArtPaLQBnzAbT06wIIGIfYGcWLtBDdGfh-E44sakcAMDuAwAaI0cr7rYmRDi0Tlc5JWA7M2aTsmcPIgbGoEzog0TTho4hnzyHCByBYTx4QFJq4hryV4IRbBynyDkGAHd4BoDwGoPIKA5QmAG1EPgIgnMobUEGMMHKfrkksWaFonecgXkLCqxRIAA
