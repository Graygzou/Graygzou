FROM python:3.8-alpine

RUN pip install requests
RUN pip install pytz


ADD entrypoint.sh /.github/actions/entrypoint.sh
ADD aoc-badges.py /.github/actions/aoc-badges.py

RUN chmod +x /.github/actions/entrypoint.sh
ENTRYPOINT ["/.github/actions/entrypoint.sh"]
