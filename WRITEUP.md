# COMP 440: Representing and Retrieving Knowledge

Claude writes your answers here as you say them. A sentence or two is enough for each. Your
Part 0 predictions stay as you first wrote them; Part 5 asks what you would change.

**Name:** Nadezhda Dominguez Salinas
**Date:** October 20, 2026

## Part 0: Predictions

### Questions that name a character, place or thing: which method will do better, and why?

The method that will perform better is keyword search as it directly scores a movie by the words and thus if we are given a name of something then we can more likely match it to see which words are shared between plot summary and my question.

### Vague descriptions: which method will do better, and why?

In vague description we are less likely to have a one to one match on name of characters, or place in the movie, therefore the embedding search does a better job at matching the closest results to each other than a direct comparison.

## Part 1: Build the TF-IDF model

### The settings you chose, and why

- `REMOVE_STOP_WORDS = True`: because it will make it easier to compare words that are shared between the question and the plot summary
- `MIN_MOVIES = 3`: because this feels like a fairly low threshold that would not remove many highly relevant words but, also would keep some names of characters that might appear in sequels or more
- `REPEATS_COUNT_LESS = True`: because it does not add value to count one word multiple times, such as if a word was bike and it appeared multiple times would not add to the compare analysis

## Part 2: Top terms

### Your movies: what do the top terms get right and wrong about what makes each one distinctive?

White Chicks: I think for white chicks the words marcus and kevin are correct and sisters are correct but the words brothers and socialities are decieviing because the plot is about sisters and socialities does not seem very reflective of the plot

21 Jump Street: for the second movie I think that students, jock, partners, drugs are very descriptive but the words joined and park are not very reflective of the plot summary, overall I think they did a better job for top words in 21 Jump Street

## Part 3: Your own searches

### Your questions, as you typed them

XXXX

### Did the movies you meant come up? What did TF-IDF get right and wrong?

XXXX

## Part 4: The question bank

### Which kind of question did TF-IDF handle best, and which worst? By how much?

XXXX

### The misses you looked at: what do they have in common?

XXXX

## Part 5: Embeddings

### What is a sentence embedding, in your own words?

XXXX

### Where does each method do better, and why?

XXXX

### Your Part 0 predictions: which held, and which would you change?

XXXX

### How might you combine the two methods?

XXXX
