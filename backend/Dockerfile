FROM golang

WORKDIR /app

COPY . .

RUN go build -o backend main.go

# Jalankan aplikasi
ENTRYPOINT ["./backend"]