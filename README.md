# mit-6-0001---problem-set-2-solved
**TO GET THIS SOLUTION VISIT:** [MIT-6.0001 – Problem Set 2 Solved](https://www.ankitcodinghub.com/product/mit-6-0001-problem-set-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116057&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MIT-6.0001 - Problem Set 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
This problem set will introduce you to the topic of creating functions in Python, as well as looping mechanisms for repeating a computational process until a condition is reached.

Note on Collaboration:

Problem 1: Basic Hangman

You will implement a variation of the classic word game Hangman. If you are unfamiliar with the rules of the game, read

http://en.wikipedia.org/wiki/Hangman_(game). D on’t be intimidated by this problem ­ it’s actually easier than it looks! We will ‘scaffold’ this problem, guiding you through the creation of helper functions before you implement the actual game.

A) Getting Started

Download the files “hangmadirectory n.py” and “words.txt”, and save them bo t yh in the samour files are e

. Run the file h angman.py before writing any code to ensure saved correctly. The code we have given you loads in words from a file. You should see the following output in your shell:

Loading word list from file…

55900 words loaded.

If you see the above text, continue on to Hangman Game Requirements. If you don’t, double check that both files are saved in the same place!

B) Hangman Game Requirements

You will implement a function called hangman that will allow the user to p and the player tries to glay hauessngman against the computer. The computer picks the word, letters in the word.

Here is the general behavior we want to implement. Don’t be intimidated! This is just a description; we will b reak this down into steps and provide further functional specs later on in the pset so keep reading!

1. The computer must select a word at random from the list of available words that was provided in words.txt

Note that words.t xt contains words in all lowercase letters.

2. The user is given a certain number of guesses at the beginning.

3. The game is interactive; the user inputs their guess and the computer either:

a. reveals the letter if it exists in the secret word

b. penalize the user and updates the number of guesses remaining

4. The game ends when either the user guesses the secret word, or the user runs out of guesses.

Problem 2 Hangman Part 1: Three helper functions

Before we have you write code to organize the hangman game, we are going to break down the problem into logical subtasks, creating three helper functions you will need to have in order for this game to work. This is a common approach to computational problem solving, and one we want you to begin experiencing.

The file hangman.py has a number of already implemented functions you can use while writing up your solution. You can ignore the code in the two functions at the top of the file that have already been implemented for you, though you should understand how to use each helper function by reading the docstrings.

1A) Determine whether the word has been guessed

First, implement the function is_word_guesseds (strings) that takes in two p , letters_guessed.., all tarametehe This funct letters ­ a rs of ion string, secret_wordsecret_word, and a list of l if secret_word etter), and has been guessed ( Falsen game has been succe other wise.i.e This function will bssfully e returns a boolean ­ True

are in letters_guessed

useful in helping you decide when the hangma

completed, and becomes an end­test for any iterative loop that checks letters against the secret word.

Example Usage:

&gt;&gt;&gt; secret_word = ‘apple’

&gt;&gt;&gt; letters_guessed = [‘e’, ‘i’, ‘k’, ‘p’, ‘r’, ‘s’ ]

&gt;&gt;&gt; print(is_word_guessed(secret_word, letters_guessed) )

False

1B) Getting the user’s guess

Next, implement the function get_guessed_word letters_guessed that takes in two p based on w. This function r hat learametetters in eturrs ­ a ns a string, secret_word, and a list of l s and underetters, scores, string that is comprised of letter letters_guessedis_word_guessed are in ! secret_word. This shoul dn’t be too different from

We are going to use an underscore followed by a space (_ ) to represent unknown letters. We could have chosen other symbols, but the combination of underscore and space is visible and easily discerned. Note that the space is super important, as otherwise it hard to distinguish whether ____ is four elements long or three. This is called usability ­ it’s very important, when programming, to consider the usability of your program. If users find your program difficult to understand or operate, they won’t use it! We encourage you to think about usability when designing your program.

Hint: In designing your function, think about what information you want to return when done, whether you need a place to store that information as you loop over a data structure, and how you want to add information to your accumulated result.

Example Usage:

&gt;&gt;&gt; secret_word = ‘apple’

&gt;&gt;&gt; letters_guessed = [‘e’, ‘i’, ‘k’, ‘p’, ‘r’, ‘s’ ]

&gt;&gt;&gt; print(get_guessed_word(secret_word, letters_guessed) )

‘_ pp_ e’

1C) Getting all available letters

list of letters, letters_guessed. This function r se English leturetterns a string s that aretha not in t is comprised of lowercase English letters ­ all lowerca

letters_guessed.

Hint: You might consider using string.ascii_lowercase, which is a st ring comprised of all lowercase letters:

&gt;&gt;&gt; import string

&gt;&gt;&gt; print(string.ascii_lowercase) abcdefghijklmnopqrstuvwxyz

Example Usage:

&gt;&gt;&gt; letters_guessed = [‘e’, ‘i’, ‘k’, ‘p’, ‘r’, ‘s’ ] &gt;&gt;&gt; print get_available_letters(letters_guessed ) abcdfghjlmnoqtuvwxyz

Problem 3 Hangman Part 2: The Game

Now that you have built some useful functions, you can turn to implementing the

function hangman, which takes one pa ) manuarameterlly set this secret word when you run t ­ the secret_word t he user is to ghis uess.

Initially, you can (and should! function – this will make it easier to test your code. But in the end, you will want the computer to select this secret word at random before inviting you or some other user to play the game by running this function.

Calling the hangman function starts up an interactive game of Hangman between the user and the computer. In designing your code, be sure you take advantage of the three helper functions, get_available_lettersis_word_guessed, that you’ve defined in the pr , get_guessed_wordevious p, a art!nd

Below are the game requirements broken down in different categories. Make sure your implementation fits all the requirements!

Game Requirements

A. Game Architecture:

1. The computer must select a word at random from the list of available words that was provided in words.txt. The functions for loading the word list and selecting a random word have already been provided for you in hangman.py.

2. Users start with 6 guesses.

3. At the start of the game, let the user know how many letters the computer’s word contains and how many guesses s/he starts with.

4. The computer keeps track of all the letters the user has not guessed so far and before each turn shows the user the “remaining letters”

Example Game Implementation:

Loading word list from file…

55900 words loaded.

Welcome to the game Hangman!

I am thinking of a word that is 4 letters long .

————-

You have 6 guesses left.

Available letters: abcdefghijklmnopqrstuvwxy z

B. User­Computer Interaction:

The game must be interactive and flow as follows:

1. Before each guess, you should display to the user:

a. Remind the user of how many guesses s/he has left after each guess.

b. all the letters the user has not yet guessed

2. Ask the user to supply one guess at a time. (Look at the user input requirements below to see what types of inputs you can expect from the user)

3. Immediately after each guess, the user should be told whether the letter is in

the computer’s word.

4. After each guess, you should also display to the user the computer’s word, with guessed letters displayed and unguessed letters replaced with an underscore and space (_ )

5. At the end of the guess, print some dashes (­­­­­) to help separate individual guesses from each other

Example Game Implementation:

(The blue color below is only there to show you what the user t yped in, as opposed to what the computer output.)

You have 6 guesses left.

Available letters: abcdefghijklmnopqrstuvwxy z

Please guess a letter: a

Good guess: _ a_ _

————

You have 6 guesses left.

Available letters: bcdefghijklmnopqrstuvwxy z

Please guess a letter: b

Oops! That letter is not in my word: _ a_ _

C. User Input Requirements:

Hint #1: Use calls to the input function to get the user ’s guess.

a. Check that the user input is an alphabet

user input to lowercase Hint #3: Since the words in wor at all times and have your game only ds.txt are lowercase, it might bhandlee easie lower to convrcase. ert the

Example Game Implementation:

You have 3 warnings left.

You have 6 guesses left.

Available letters: bcdefghijklmnopqrstuvwxy z

Please guess a letter: s

Oops! That letter is not in my word: _ a_ _

————

You have 5 guesses left.

Available letters: bcdefghijklmnopqrtuvwxy z

Please guess a letter: $

Oops! That is not a valid letter. You have 2 warnings left: _ a_ _

D. Game Rules:

1. The user starts with 3 warnings.

2. If the user inputs anything besides an alphabet (symbols, numbers), tell the user that they can only input an alphabet.

b. If the user has no remaining warnings, they should lose one guess.

3. If the user inputs a letter that has already been guessed, print a message telling the user the letter has already been guessed before.

b. If the user has no warnings, they should lose one guess.

4. If the user inputs a letter that hasn’t been guessed before and the letter is in

5. the secret word, the user loses Consonants: no guesses. t been guessed and the If the user inputs a consonant that ha sn’

consonant is not in the secret word, the user loses one g uess if it’s a consonant.

6. Vowels: If the vowel ha sn’ guesses. Vowels are t been guessed and the vowa, e , i, o, ael is not in tnd u . y doehes not secret word, the user loses two count as a vowel.

Example Implementation:

You have 5 guesses left.

Available letters: bcdefghijklmnopqrtuvwxy z

Please guess a letter: t

Good guess: ta_ t

————

You have 5 guesses left.

Available letters: bcdefghijklmnopqrtuvwxy z

Please guess a letter: e

Oops! That letter is not in my word: ta_ t

————

You have 3 guesses left.

Available letters: bcdfghijklmnopqrtuvwxyz

Please guess a letter: e

Oops! You’ve already guessed that letter. You now have 2 warnings :

ta_ t

E. Game Termination:

1. The game should end when the user constructs the full word or runs out of guesses.

2. If the player runs out of guesses before completing the word, tell them they lost and reveal the word to the user when the game ends.

3. If the user wins, print a congratulatory message and tell the user their score.

4. The total score is the number of guesses_remaining on ce trs in he user hasecret_words . guessed the secret_word times the number of unique l ette

Total score = guesses_remaining* number unique letters in secret_word

Example Implementation:

You have 3 guesses left.

Available letters: bcdfghijklnopquvwxyz

Please guess a letter: c

Good guess: tact

————

Congratulations, you won!

Your total score for this game is: 9

Example Implementation:

You have 3 guesses left.

Available letters: bcdfghijklnopquvwxyz

Please guess a letter: n

Good guess: dolphin

————

Congratulations, you won!

Your total score for this game is: 21

F. General Hints:

1. Consider writing additional helper functions if you need them.

a.b. secret_wordletters_guessed: The word to guess. This is a functi on.s that have been gue lready used as tssed so far. If the parameterhey name for the hangman: The letterdy in letters_guessed dy guessed tha, you should p t but do not printenalize a guess a letter that is alrea message telling them they’ve alrea them for it.

c. guesses_remaining: The number of guesses the user has le the penalty for choosing an incorrect vftowe. Notel is that in our example game,

different than the penalty for choosing an incorrect consonant.

G. Example Game:

Look carefully at the examples given above of running hangman each gue, as t ss of a lehat sugtter.gests examples of information you will want to print out after

Note: Try to make your print statements as close to the example game as possible!

The output of a winning game should look like thi s. (The blue col or below is only there to show you what the user typed in, as opposed to what the computer output.) Loading word list from file…

55900 words loaded.

Welcome to the game Hangman!

I am thinking of a word that is 4 letters long .

You have 3 warnings left.

————-

You have 6 guesses left.

Available letters: abcdefghijklmnopqrstuvwxy z

Please guess a letter: a

Good guess: _ a_ _

————

You have 6 guesses left.

Available letters: bcdefghijklmnopqrstuvwxy z

Please guess a letter: a

Oops! You’ve already guessed that letter. You have 2 warnings left : _ a_ _

————

You have 6 guesses left.

Available letters: bcdefghijklmnopqrstuvwxy z

Please guess a letter: s

Oops! That letter is not in my word.

Please guess a letter: _ a_ _

————

You have 5 guesses left.

Available letters: bcdefghijklmnopqrtuvwxy z

Please guess a letter: $

Oops! That is not a valid letter. You have 1 warnings left: _ a_ _

————

You have 5 guesses left.

Available letters: bcdefghijklmnopqrtuvwxy z

Please guess a letter: t

Good guess: ta_ t

————

You have 5 guesses left.

Available letters: bcdefghijklmnopqrtuvwxy z

Please guess a letter: e

Oops! That letter is not in my word: ta_ t

————

You have 3 guesses left.

Available letters: bcdfghijklmnopqrtuvwxyz

Please guess a letter: e

Oops! You’ve already guessed that letter. You have 0 warnings left : ta_ t

————

You have 3 guesses left.

Available letters: bcdfghijklmnopqrtuvwxyz

Please guess a letter: e

Oops! You’ve already guessed that letter. You have no warnings lef t so you lose one guess: ta_ t

————

You have 2 guesses left.

Available letters: bcdfghijklnopquvwxyz

Please guess a letter: c

Good guess: tact

————

Congratulations, you won!

Your total score for this game is: 6

And the output of a losing game should look like thi s…

Loading word list from file…

55900 words loaded.

Welcome to the game Hangman!

I am thinking of a word that is 4 letters lon g

You have 3 warnings left.

———–

You have 6 guesses left

Available Letters: abcdefghijklmnopqrstuvwxy z

Please guess a letter: a

Oops! That letter is not in my word: _ _ _ _

———–

You have 4 guesses left

Available Letters: bcdefghijklmnopqrstuvwxy z

Please guess a letter: b

Oops! That letter is not in my word: _ _ _ _

———–

You have 3 guesses left

Available Letters: cdefghijklmnopqrstuvwxy z

Please guess a letter: c

Oops! That letter is not in my word: _ _ _ _

———–

You have 2 guesses left

Available Letters: defghijklmnopqrstuvwxyz

Please guess a letter: 2

Oops! That is not a valid letter. You have 2 warnings left: _ _ _ _

­­­­­­­­­­­

You have 2 guesses left

Available Letters: defghijklmnopqrstuvwxyz

Please guess a letter: d

Oops! That letter is not in my word: _ _ _ _

———–

You have 1 guesses left

Available Letters: efghijklmnopqrstuvwxyz

Please guess a letter: e

Good guess: e_ _ e

———–

You have 1 guesses left

Available Letters: fghijklmnopqrstuvwxyz

Please guess a letter: f

Oops! That letter is not in my word: e_ _ e

———–

Sorry, you ran out of guesses. The word was else .

“__main__”:

#secret_word = choose_word(wordlist)

#hangman(secret_word)

Problem 4 Hangman Part 3: The Game with Hints

For example, if the hidden word is “tact”, and you have so far guessed the letter “t”, so that you know the solution is “t_ _ t”, where you need to guess the two missing letters, it might be nice to know that the set of matching words (at least based on what the computer initially loaded) are:

tact tart taut teat tent test text that tilt tint toot tort tout trot tuft twit

We are going to have you create a variation of Hangman (we call this

property that if you guess the specihangman_with_hints, and have provided an i al characternitia * the computer will fil scaffold for writingnd it), with t all the wheords

from its loaded list that might match your current guessed word, and print out each of them. Of course, we don’t recommend trying this at the first step, since this will print out all 55,900 words that we loaded! But if you are getting close to an answer and are running out of guesses, this might help.

To do this, we are going to ask you to first complete two helper functions:

3A) Matching the current guessed word

‘t_ _ t’). other_word is a normal English word.

This function should return True if the guessed l etters of my_word match the corresponding letters of other_word. It should r eturn False if the two words are not of the same length or if a guessed letter in my_word does not match the corresponding character in other_word.

Remember that when a letter is guessed, your code reveals all the positions at which that letter occurs in the secret word. Therefore, the hidden letter (_ ) cannot be one of the letters in the word that has already been revealed.

Example Usage:

&gt;&gt;&gt; match_with_gaps(“te_ t”, “tact”)

False

&gt;&gt;&gt; match_with_gaps(“a_ _ le”, “banana”)

False

&gt;&gt;&gt; match_with_gaps(“a_ _ le”, “apple”)

True

&gt;&gt;&gt; match_with_gaps(“a_ ple”, “apple”) False

3B) Showing all possible matches

guessed word, in other words,

This function should print out all words in wordlist ( notice where we have defined this at the beginning of the file, line 51) that match my_word. It should p rint “No matches found” if there are no matches.

Example Usage:

&gt;&gt;&gt; show_possible_matches(“t_ _ t”)

tact tart taut teat tent test text that tilt tint toot tort tout trot tuf t twit

&gt;&gt;&gt; show_possible_matches(“abbbb_ “)

No matches found

&gt;&gt;&gt; show_possible_matches(“a_ pl_ “) ample amply

3C) Hangman with hints

Now you should be able to rhangman_with_hints eplicate the code you wrote for hangman ca as tse whehere bod they of user

, then make a small addition to allow for t he

can guess an asterisk (*), in which case the computer will print out all the words that match that guess.

The user should not lose a guess if the guess is an asterisk.

Comment out the lines of code you used to play the original Hangman game: secret_word = choose_word(wordlist) hangman(secret_word)

And un­comment out these lines of code we’ve provided at the bottom of the file to play your new game Hangman with Hints: #secret_word = choose_word(wordlist)

#hangman_with_hints(secret_word)

Sample Output:

The output from guessing an asterisk should look like the sample output below. All other output should follow the Hangman game described in Part 2 above.

Loading word list from file…

55900 words loaded.

Welcome to the game Hangman!

I am thinking of a word that is 5 letters long .

——–

You have 6 guesses left.

Available letters: abcdefghijklmnopqrstuvwxy z

Please guess a letter: a

Good guess: a_ _ _ _

——–

You have 6 guesses left.

Available letters: bcdefghijklmnopqrstuvwxy z

Please guess a letter: l

Good guess: a_ _ l_

——–

You have 6 guesses left.

Available letters: bcdefghijkmnopqrstuvwxy z

Please guess a letter: * Possible word matches are:

addle adult agile aisle amble ample amply amyls angle ankle appl e apply aptly arils atilt

——–

You have 6 guesses left.

Available letters: bcdefghijkmnopqrstuvwxy z

Please guess a letter: e

Good guess: a_ _ le

——–

This completes the problem set!

MIT OpenCourseWare https://ocw.mit.edu

6.0001 Introduction to Computer Science and Programming in Python

For information about citing these materials or our Terms of Use, visit: https://ocw.mit.edu/terms.
