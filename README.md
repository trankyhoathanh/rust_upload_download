# Download Upload API
Tạo folder /files
cargo run (port = 8080)

# Example curl
curl --location --request POST 'http://localhost:8080/upload' \
--header 'Content-Type: multipart/form-data' \
--form 'file=@/Volumes/Task/test001.png'

curl --location --request POST 'http://localhost:8080/upload' \
--header 'Content-Type: multipart/form-data' \
--form 'file=@/Volumes/Task/test002.png'

