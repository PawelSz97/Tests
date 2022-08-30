# Tests
Unit test- python

# werfyikacja pełnoletnośći użytkownika 

def is_adult(age: int) -> bool:
    return age > 18
def test_is_adult():
    assert is_adult(20)
def test_is_not_adult():
    assert not is_adult(16)
