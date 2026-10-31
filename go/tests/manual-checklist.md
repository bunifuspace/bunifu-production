# Manual verification checklist

- [ ] Run from localhost or HTTPS.
- [ ] Add an allowance and verify balance increases.
- [ ] Add an expense and verify balance decreases.
- [ ] Edit and delete transactions.
- [ ] Confirm week starts Sunday and ends Saturday.
- [ ] Edit budget allocations; allocations above allowance should be rejected.
- [ ] Add menu item and change its price.
- [ ] Log a meal and verify a linked Food expense is created.
- [ ] Delete a meal and verify its linked expense is deleted.
- [ ] Log 200 ml, 500 ml and 1 litre of water.
- [ ] Record a bottled-water purchase and verify linked Water expense.
- [ ] Delete a water purchase and verify linked expense deletion.
- [ ] Check analytics in weekly, monthly and all-time modes.
- [ ] Export JSON, clear data, then restore JSON.
- [ ] Reload and verify IndexedDB data persists.
- [ ] Install PWA, disconnect network and reopen the cached shell.
- [ ] Check responsive navigation on a phone-sized viewport.
