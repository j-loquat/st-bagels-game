# st-bagels-game

This is the classic Bagels number-guessing game - but done in Streamlit and leveraging the Streamlit Chat components.

## Description

#### The Bagels Game
* I will think of a {NUM_DIGITS}-digit number.
* Each digit is unique.
* You will try to guess what it is in {MAX_GUESS} guesses or less.

The clues I give (one or more depending on situation) are... 
| **When I say** | **That means**                                 |
|-----------------|-------------------------------------------------|
| _Bagels_        | None of the digits are correct.                 |
| _Pico_          | One digit is correct but in the wrong position. |
| _Fermi_         | One digit is correct and in the right position. |


## Getting Started

Run directly on the Internet via published app URL: 
https://st-bagels-game.streamlit.app/

Run locally via streamlit python component.

### Dependencies

* Python 3.9+
* streamlit
* web browser

### Installing

* copy bagels-streamlit.py to your computer
* in terminal:> pip install streamlit

### Executing program

* in terminal:> streamlit run bagels-streamlit.py
* open web browser to localhost link shown in terminal

## Authors

Contributors names and contact info

* David Jackson
* [GitHub](https://github.com/j-loquat)

## Version History

* 0.1
    * Initial Release

## License

This project is free for all to use.

## Acknowledgments

Inspiration, code snippets, etc.
* [Invent Your Own Computer Games with Python, 4th Edition Paperback – Dec 16 2016 by Al Sweigart (Author)](https://a.co/d/d4Traa2)
* [Streamlit Chat Elements](https://docs.streamlit.io/library/api-reference/chat)
