Write a PL/SQL program to list all supplier rows, in supplier number order. Each supplier row should be immediately followed in the listing by all part rows for parts supplied by that supplier, in part number order as follows. Suppliers who do not supply any parts should still be listed. Your program should contain a cursor for suppliers and a parameterized cursor for parts.
+----------+-------------------------+----------+-------------------------+
|    S#    |          SNAME          |  STATUS  |          CITY           |
+==========+=========================+==========+=========================+
|    S1    |          Smith          |    20    |          London         |
+----------+-------------------------+----------+-------------------------+
|                                                                         |
|    +------+----------------+------------+--------+------------------+   |
|    |  P#  |     PNAME      |   COLOR    | WEIGHT |       CITY       |   |
|    +======+================+============+========+==================+   |
|    |  P1  |     Nut        |   Red      |   12   |       London     |   |
|    +------+----------------+------------+--------+------------------+   |
|                                                                         |
+----------+-------------------------+----------+-------------------------+
|    ...                                                                  |
|                                                                         |
+----------+-------------------------+----------+-------------------------+
|    S6    |      yourname           |    20    |          Ottawa       |
+----------+-------------------------+----------+-------------------------+
|                                                                         |
|    +------+----------------+------------+--------+------------------+   |
|    |  P#  |     PNAME      |   COLOR    | WEIGHT |       CITY       |   |
|    +======+================+============+========+==================+   |
|                                                                         |
+----------+-------------------------+----------+-------------------------+
Part 2: Do Part 1 again using embedded SQL in C (50%)

The requirement is the same.
