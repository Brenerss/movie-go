# Movie Go 🎬

A fast and lightweight RESTful API for movie data management, built with Go.

## 🚀 Overview

Movie Go is a backend service designed to handle movie catalogs. It provides essential endpoints to create, read, update, and delete movie records.

## 🛠 Technologies

*   **Go** (Golang)
*   Standard `net/http` library (or specify your router, e.g., Gin/Mux)

## ⚙️ Prerequisites

Make sure you have [Go](https://go.dev/doc/install) installed on your machine.

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Brenerss/movie-go.git
   ```
2. Navigate to the project directory:
   ```bash
   cd movie-go
   ```
3. Install dependencies:
   ```bash
   go mod tidy
   ```

## 🏃‍♂️ Running the Application

Start the server by running:
```bash
go run main.go
```
The API will be available at `http://localhost:8080`.

## 📡 API Endpoints (Example Structure)

| Method | Endpoint       | Description                         |
| :---   | :---           | :---                                |
| `GET`  | `/movies`      | Returns a list of all movies        |
| `GET`  | `/movies/{id}` | Returns details of a specific movie |
| `POST` | `/movies`      | Creates a new movie entry           |
| `PUT`  | `/movies/{id}` | Updates an existing movie           |
| `DELETE`| `/movies/{id}`| Deletes a movie                     |

## 📝 License

This project is open-source and available under the MIT License.
