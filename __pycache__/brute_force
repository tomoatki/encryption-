
message = 'GUVF VF ZL FRPERG ZRFFNTR.'
LETTERS = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'

for key in range(len(LETTERS)):

    # it is important to set translated to blank string
    #previous value is cleared
    translated = ''

    # The rest of the program is the same as the orginal Caesar program:
    for symbol in message:
        if symbol in LETTERS:
            num = LETTERS.find(symbol)
            num = num - key

            if num < 0:
                num = num + len(LETTERS)

            # add numbers symbol at the end of translated
            translated = translated + LETTERS[num]

        else:
            translated = translated + symbol

        # display the current key being tested with decyption
    print('Key #%s: %s' % (key, translated))
