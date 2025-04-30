# Favourtie Vim Movements
1. smth + i / a + character
    do smth inside or around the character
    example:
        d i " -> delete inside double quotes
        y i ( -> yank inside parentheses
        v a ) -> visual select around parentheses
        c i ' -> change inside single quotes

1. number + i + write some text + ctrl-c -> inserts texts and repeats it number times
    example:
        5 i hello world ctrl-c -> inserts hello world 5 times

1. c w -> delete word and enter insert mode

1. g d -> go to definition

1. ctrl o -> go to previous location in the jump list

1. ctrl i -> go to next location in the jump list

1. g ; -> go to previous change location

1. g , -> go to next change location
