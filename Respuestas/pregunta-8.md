db.libros.find(
  { categoria: "informatica" }
).explain("executionStats");