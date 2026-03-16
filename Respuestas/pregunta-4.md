db.libros.updateOne(
  { titulo: "Sistemas Distribuidos" },
  { $set: { anio: 2023 } }
);