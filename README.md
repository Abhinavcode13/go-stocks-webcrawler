# Project flow - go-webcrawler

## Overview

This project is a simple Go webcrawler designed to fetch historical stock prices from `Yahoo Finance` and plot them as an `ASCII graph`. It utilizes the gocolly library for web scraping and the asciigraph library for plotting the data.

## Project Architecture

![Project](https://github.com/Abhinavcode13/go-stocks-webcrawler/assets/126642111/96841cbf-16d5-4f44-b432-95e9284da0b1)

## Prerequisites
- Go (version 1.15 or higher)
- Internet connection (to fetch stock prices from Yahoo Finance)

## Libraries Used
- [gocolly](https://github.com/gocolly/colly): A powerful and easy-to-use web scraping library for Go.
- [asciigraph](https://github.com/guptarohit/asciigraph): A Go library to plot data in the terminal as ASCII graphs.

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/go-webcrawler.git
    cd go-webcrawler
    ```

2. Install the necessary libraries:
    ```sh
    go get -u github.com/gocolly/colly
    go get -u github.com/guptarohit/asciigraph
    ```

## Usage
1. Build the project:
    ```sh
    go build -o stockcrawler main.go
    ```

2. Run the project with a stock symbol (e.g., AAPL for Apple Inc.):
    ```sh
    ./stockcrawler -stock=AAPL
    ```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
