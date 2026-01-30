# telegram-rss-bot
import feedparser import telegram import time  TOKEN = 8468607034:AAFvQ299ZaGcqUIeFF9viFwrw_iQlOy4iU8CHANNEL = @Akbar_yakubov_bot= telegram.Bot(token=TOKEN) rss_url = "https://www.espn.com/espn/rss/soccer/news"  sent_links = set()  while True:     feed = feedparser.parse(rss_url)     for entry in feed.entries[:5]:         if entry.link not in )
