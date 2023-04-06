# awk

Basic syntax
Command	Deskripsi
awk '{print}' <file>	Menampilkan seluruh isi file
awk '/<pattern>/' <file>	Menampilkan baris dalam file yang sesuai dengan pola yang diberikan
awk '/<pattern>/ {print}' <file>	Menampilkan baris dalam file yang sesuai dengan pola yang diberikan
awk '{print $<column_number>}' <file>	Menampilkan kolom tertentu dalam file
awk '{print $0}' <file>	Menampilkan seluruh baris dalam file
awk '/<pattern>/ {print $<column_number>}' <file>	Menampilkan kolom tertentu dalam baris yang sesuai dengan pola yang diberikan
