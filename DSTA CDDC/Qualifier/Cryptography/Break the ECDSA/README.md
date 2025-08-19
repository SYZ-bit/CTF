# Break the ECDSA

## Description

As BH-2000 was cleaning the office, it lost Dex's key.
Now, without the key, Dex can't even open his cabinet for his combat suit.
Dex needs the suit to save whoever and whatever he needs to, so BH-2000 wants to recover Dex's key.

Dex says he used a combination of English words to create the key.
Unfortunately, he's forgotten some of the words he used.
Let's find the forgotten words and recover the key with whatever the information we have on hand!

words : BIP-39 SECP256k1 {word1} 5eed r4nd0m {word2} g00d 5olve c0ffe {word3} pe4nut 5mart
r = 81210355722750344493541519494641458710145722871994877785183554697310523407018
h1 = 45643200378651069483892104393394606812504455659831083323743202489147422538955
h2 = 74831345439009646272332597737070016777412939113737083148228963710487431876647
s1 = 110764343964105699917226529930289538481215574456544978805357332521308340464732
s2 = 90138993253633063487274662700800979929978777245182171200537527514756442604713

Oh, you thought it was a physical key?
Duh, what year do you think we're in? :P

FLAG Format : CDDC2025{word1_word2_word3_privatekey}
※ Private key value is written in hexadecimal
Ex) 0x1234567890abcdef
 

