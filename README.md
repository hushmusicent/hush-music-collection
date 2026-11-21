# Hush Collection — Comics, Cards & Toys
Build v2026.11.20.4 — AI Studio

Single-file app: `index.html` (34,749 bytes). No sign-in, no server.
Open in AI Studio preview, browser, or HTML Viewer on phone.

## Snap & Price — new in v3

After pricing, pick one:
- **📚 Put in my collection** — saves as KEEP, counts in your total value, no bidding
- **💰 List it for sale** — saves as FOR SALE, starts at $0.99, takes bids

You can flip a kept item to For sale later from Edit.
1. Tap "📸 Snap it — check price", take a photo (front, and back for cards)
2. Tap '🔍 Identify with Lens' — it shares the photo straight to the Lens app on your phone via Android share. Pick Lens in the share sheet, Lens names the item. If share is not available, it saves the photo and opens lens.google.com/upload — pick the saved photo there. Lens needs a photo file, it cannot read a photo straight from a web page, so sharing is how it works. Bing Visual and eBay Camera also linked.
3. Type that name in. Price rows appear for every site for that type.
4. Tap each site, look at what it ACTUALLY SOLD for, type that price in. App shows low / high / average. Save as item uses the average as est. value.

Per-item "📸 Price" button re-opens Snap & Price pre-filled with that item.

## Marketplace links (v1)
Every item has Sell / price check buttons, pre-filled:
- Comics: eBay Sold, eBay, MyComicShop, Heritage, Whatnot, Mercari
- Cards: eBay Sold, TCGplayer, PriceCharting, eBay, COMC, Whatnot, Mercari
- Toys: eBay Sold, eBay, Mercari, Whatnot, Amazon, ToyWiz

## Honest limit
No site lets another app pull its live sold prices straight in without a paid account / API key, and no photo app can name a comic/card/toy from a picture alone without a vision service. So: Lens names it from the photo, the sites show sold prices, this app averages them in one place. Bidding/checkout happens on the marketplace site.
If he wants fully automatic pricing later, that needs eBay Browse API + TCGplayer/PriceCharting API keys — separate job, not in AI Studio alone.

## AI Studio / GitHub
1. Create empty public repo `hush-music-collection` on github.com/hushmusicent
2. Upload/push `index.html`
3. In AI Studio (aistudio.google.com), Step 1 pull from that repo. Check top says Build v2026.11.20.3.
