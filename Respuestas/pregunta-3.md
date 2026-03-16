db.libros.find(
  { categoria: "informatica" },
  { _id: 0, titulo: 1, autor: 1 }
);