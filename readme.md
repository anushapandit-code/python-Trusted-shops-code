Excecution of the test:
1. TestTrustedShops
pytest --browser "BROWSER NAME" --url "URL" --html="ADDRESS OF THE REPORt FILE" --self-contained-html

Example : pytest --browser chrome --url https://www.trustedshops.de/bewertung/info_X77B11C1B8A5ABA16DDEC0C30E7996C21.html --html=report_1.html --self-contained-html

2. test_one_star.py
pytest test_one_star.py
