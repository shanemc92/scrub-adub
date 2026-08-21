# Demo data

Entirely fictional. Names, addresses, Eircodes, IPs, cards and keys are all invented
for testing the detectors -- none of it corresponds to a real person or system.

| File | What it exercises |
|---|---|
| `incident-notes.txt` | Free text: NAME, EMAIL, PHONE, IP, MAC, HOST, ADDRESS, EIRCODE, SECRET, JWT, CARD, IBAN |
| `users.csv` | Regex detectors plus column selection (`employee_id`, `workstation`) |
| `tickets.json` | Nested JSON paths (`tickets[].asset`, `tickets[].cost_centre`) |
