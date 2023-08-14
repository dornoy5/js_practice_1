# install server
    npm install -g json-server
# run server
    json-server --watch db.json

# server address
    http://localhost:3000/students

# sample data
{
    "students": [
        {
            "sname": "waga",
            "age": 17
        },
        {
            "sname": "baga",
            "age": 5
        },
        {
            "sname": "gaga",
            "age": 7
        }
    ]
}