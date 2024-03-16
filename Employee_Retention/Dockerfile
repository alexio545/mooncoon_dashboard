FROM python:3.8-slim-buster


WORKDIR /app

COPY . /app
RUN pip install -r requirements.txt

# Copy the application code to the working directory
COPY . .

# Expose the port on which the application will run
EXPOSE 8000


CMD ["uvicorn", "app.application.src.app:app", "--host", "0.0.0.0", "--port", "8000"]






































