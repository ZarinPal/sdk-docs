# zip

## SDK checklist

### Internals

- [ ] HTTP client
  - [ ] API handlers
    - [ ] REST handlers
    - [ ] GraphQL handlers
  - [ ] exceptions
    - [ ] HTTP exceptions
    - [ ] validation exceptions
    - [ ] API exceptions
  - [ ] rate limiting and allow retry **
  - [ ] timeouts
  - [ ] HTTP headers
    - [ ] formatted user agent
    - [ ] json accept header
    - [ ] json content type header
  - [ ] analytics ** disable/enable config
    - [ ] performance
    - [ ] error reports

### Services

- Payment Gateway
  - [ ] request new Payment
  - [ ] Payment start
  - [ ] verify Payment
  - [ ] unverified Payment

- Payment Refound
  - [ ] request new Payment Refound
  - [ ] retrieve Payment Refound by id
  - [ ] Payment Refound receipt link

- Invoice
  - [ ] request new Invoice
  - [ ] Invoice start payment (with zarinpal)
  - [ ] Invoice start payment (Payment Gateway)
  - [ ] retrieve Invoice (list, by id)

- Payout
  - [ ] request new Payout
  - [ ] deactivate Payout
  - [ ] retrieve Payout (list, by id)

- Instant Payout
  - [ ] request new Instant Payout
  - [ ] retrieve Instant Payout (list, by id)
  - [ ] Instant Payout receipt link

- oauth
  - [ ] -----

- [ ] User
  - [ ] retrieve User

- [ ] Terminal
  - [ ] retrieve Terminal (list, by id)
  - [ ] add Terminal
  - [ ] edit Terminal

- [ ] Bank Account
  - [ ] retrieve BankAccount (list, by id)
  - [ ] add BankAccount
  - [ ] edit BankAccount

- [ ] Payment Session
  - [ ] retrieve PaymentSession (list, by id)

- [ ] Reconciliation
  - [ ] retrieve Reconciliation (list, by id)
