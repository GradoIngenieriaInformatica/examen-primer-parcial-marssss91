db.libros.aggregate([
  {
    $group: {
      _id: "$categoria",
      total_libros: { $sum: 1 }
    }
  }
]);