# YNAB Reconcile helper

1. Export transactions from bank
2. Export transactions from YNAB
3. Update variables at the top of the script
4. `bundle install`
5. `bundle exec ruby reconcile.rb`

Matches transactions of the same amount within seven days of each other and lets you determine which transactions are missing from YNAB or your bank. Use `reconciler.ynab_unmatched`, `reconciler.bank_unmatched`, and `reconciler.ynab_multimatched` to explore matches.