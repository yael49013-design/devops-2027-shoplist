FROM python:3.12-slim  .#image של הגרסא המדדויקת.

WORKDIR /app           .# ניתוב של התיקייה.

COPY requirements.txt . .# העתקת קבצי הספריות.
RUN pip install --no-cache-dir -r requirements.txt #. הרצה של ההתקנות

COPY app.py .  .# העתקת הקוד.

EXPOSE 8000    .# שיוך לפורט המתאים.

CMD ["python", "app.py"] .#פקודה שתפעיל את האפליקצייה.
