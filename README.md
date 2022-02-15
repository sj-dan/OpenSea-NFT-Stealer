# OpenSea NFT Stealer

The sole purpose of this script is to download any NFT collection from [OpenSea](https://opensea.io).

---

## Setup

Prerequisites:

- Python 3.9 or above
- A brain

#### Step 1: Download the script

To download the script, either use `git clone` or click "Code" > "Download ZIP" on the GitHub page.

#### Step 2: Install dependencies

To install the dependencies for the script, simply run `pip install -r requirements.txt`.

#### Step 3: Choose your collection

Find the collection name you want to scrape on OpenSea by looking at end of the collection URL. For example, the [Lazy Lions](https://opensea.io/collection/lazy-lions) collection has the name "lazy-lions" (opensea.io/collection/**lazy-lions**).

#### Step 4: Run the script

Now, just run the script with the collection name at the end as so:

On Linux, just type `python3 opensea.py lazy-lions` in the terminal.

On Windows, just type `py opensea.py lazy-lions` in the command line.

On MacOS, you may run it the same as Linux. There are many different ways to do it, ([Google it](https://google.com/?q=how+to+open+python+script+on+macos))

---

## How does it work?

Basically, the OpenSea website allows for scripts like this one to reach into their system via an API. Using this API, we fetch the amount of items in the collection of choice, and split it into 50-item chunks each, and start downloading them. Everything is automated, except for setting the name of the collection.

---

## Why did I make this?

2 reasons: Firstly, for the funny. Secondly, out of spite for these stupid [#RightClickVictim](https://mobile.twitter.com/hashtag/RightClickVictim)s. I'm tired of all these NFT junkies constantly talking about how they're victims to screenshotting, and how screenshotting is property theft. So to rub salt in their exaggerated wounds, here is a script that downloads literally every NFT in any collection on the most popular NFT trading website.
