# Word Counter App

A simple web application built with **Django** that counts words and analyzes word frequency in any text a user submits.

## About

This project was built to learn the fundamentals of full-stack web development with Django, including the MVT (Model-View-Template) architecture, URL routing, and processing user input server-side.

## Features

- Submit any block of text or article through a simple form
- Calculates the total word count
- Generates a frequency breakdown showing how many times each word appears
- Displays results on a dedicated results page

## Tech Stack

- Python
- Django
- SQLite (database)
- HTML (templates)

## How It Works

1. The homepage (`/`) displays a form where the user pastes in text
2. On submission, the app sends the text to the `/result/` route
3. A custom word-counting function processes the text and returns:
   - Total word count
   - A dictionary of word frequencies
4. Results are rendered on the results page

## Project Structure
