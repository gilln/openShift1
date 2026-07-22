const express = require("express");

const app = express();
const PORT = process.env.PORT || 8080;

// Middleware
app.use(express.json());
app.use(express.urlencoded({ extended: true }));

// Routes
app.get("/", (req, res) => {
    res.send("Hello, GillN!");
});

app.get("/api/users", (req, res) => {
    res.json([
        { id: 1, name: "gilln1" },
        { id: 2, name: "gilln2" }
    ]);
});
