# Flash Card - French Learning Tool

A simple flash card application built with Python's Tkinter library to help users learn French vocabulary. This project allows users to review French words along with their English translations, mark words as known or unknown, and review unknown words later.



## Overview

This project was developed as a personal learning tool to enhance French vocabulary retention. It displays flash cards with French words on one side and their English translations on the other. Users can mark words they don't know (wrong) or know (right) and flip the card to reveal the translation. When the session is finished, the application shows a summary of unknown words.

## Features

- **Random Flash Card Generation:**  
  Reads from a CSV file to randomly select a French word and its English translation.

- **Interactive Card Flipping:**  
  Flip the card to view the English translation of the French word.

- **User Response Handling:**  
  Mark a word as "right" if known or "wrong" if unknown. Unknown words are tracked for review.

- **Review Unknown Words:**  
  Upon closing the main window, a new window displays a summary of words that were marked as unknown.

- **Graphical User Interface:**  
  Utilizes custom images for flash cards and buttons to provide an engaging user experience.

## Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/YourUsername/FlashCard.git
   cd FlashCard
