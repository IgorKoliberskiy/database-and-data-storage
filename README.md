db.books.insertOne(
  {
    title: "book-1",
    description: "desc book-1",
    authors: "author book-1"
  }
)

db.books.insertOne(
  {
    title: "book-2",
    description: "desc book-2",
    authors: "author book-2"
  }
)

db.books.find(
  { title: "book-1" }
)

db.books.updateOne(
  { _id: 1 },
  { $set: { description: "desc book-1", authors: "author book-1" }
)
