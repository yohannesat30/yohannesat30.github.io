# Activity 2 · Guard the form (15 minutes, pairs)

Little Lemon's outdoor tables seat **up to 6**. HTML cannot check that: it checks one field at a
time, and this rule joins two fields (seating and party size).

## Build (8 minutes)
1. Open `book.js`, block 3, function `checkBooking`.
2. Add one more `else if`: when **Outdoor** is chosen **and** the party is more than 6, set
   `problem` to `Outdoor tables seat up to 6. Please choose Indoor or call us.`
3. You already have `outdoorInput` (block 1) and `party` (inside `checkBooking`). You need `&&`.

## Swap and break (7 minutes) — on your partner's laptop
1. Outdoor + 7 guests. Refused?
2. Outdoor + 6 guests. Allowed? (6 is not *more than* 6.)
3. Indoor + 7 guests. Allowed?
4. DevTools → Elements. Delete `required` from the Name input. Submit with no name. What happens?
5. In `book.html`, delete the line `<script src="book.js" defer></script>`. Save. Book for yesterday.
   Did it go through?

**Write one sentence:** after check 5, who still has to check every booking, and when do we build it?
