---
# An instance of the Pages widget.
widget: collection

# This file represents a page section.
headless: true

# Order that this section appears on the page (place after the "About" section).
weight: 40

title: "News"
subtitle: ""

content:
  # Filter on criteria.
  filters:
    folders:
      - news
  count: 5  # Number of news articles to display (0 = show all)
  order: desc  # Show newest articles first

design:
  # Choose a view for the listings:
  view: List  # Options: List, Card, etc.
  columns: '1'  # Number of columns for display
---

