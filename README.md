<html><head><style>
                                 table {
                                 border-collapse: collapse;
                                 width: 80%;
                                 margin: auto;
                                 }
                                 
                                 th, td {
                                 border: 1px solid black;
                                 padding: 10px;
                                 text-align: center;
                                 }
                                 
                                 th {
                                 background-color: #f0f0f0;
                                 }
                                 
                                 img {
                                 width: 100px;
                                 height: 150px;
                                 }
                                 
                                 select {
                                 display: block;
                                 margin: 10px auto;
                                 }
                                 </style>
                                 <script>
                                 function filterByGenre() {
                                 var genre = document.getElementById("genre").value;
                                 var rows = document.getElementsByTagName("tr");
                                 for (var i = 1; i < rows.length; i++) {
                                 var cells = rows[i].getElementsByTagName("td");
                                 var show = false;
                                 for (var j = 1; j < cells.length; j++) {
                                 var movieGenre = cells[j].getAttribute("data-genre");
                                 if (genre == "Todos" || movieGenre == genre) {
                                 show = true;
                                 }
                                 }
                                 if (show) {
                                 rows[i].style.display = "";
                                 } else {
                                 rows[i].style.display = "none";
                                 }
                                 }
                                 }
                                 
                                 function filterByRating() {
                                 var rating = document.getElementById("rating").value;
                                 var rows = document.getElementsByTagName("tr");
                                 for (var i = 1; i < rows.length; i++) {
                                 var cells = rows[i].getElementsByTagName("td");
                                 var show = false;
                                 for (var j = 1; j < cells.length; j++) {
                                 var movieRating = cells[j].getAttribute("data-rating");
                                 if (rating == "Todos" || movieRating == rating) {
                                 show = true;
                                 }
                                 }
                                 if (show) {
                                 rows[i].style.display = "";
                                 } else {
                                 rows[i].style.display = "none";
                                 }
                                 }
                                 }
                                 </script>
                                 </head>
                                 <body>
                                 <h1>Tabela de horários de cinema</h1>
                                 <select id="genre" onchange="filterByGenre()">
                                 
                                 </select>
                                 <table>
                                 <tbody><tr>
                                 <th>Horário</th>
                                 <th>tteuw e a disgrasa</th>
                                 <th>tteuw pinas</th>
                                 <th>tteuw e o curio</th>
                                 </tr>
                                 <tr>
                                 <td>10h</td>
                                 <td data-genre="Animação" data-rating="Livre"><a href="https://www.youtube.com/watch?v=Mf7bC8ObERI"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX7oaJhUihKA3Dm61NHrcFJ3on-aKXFyAnjGRsE2C0Pjdg48MdT2mBlWY15ZBxf3L1DKA&amp;usqp=CAU&quot; alt=" cartaz="" do="" filme="" 1"=""></a></td>
                                 <td data-genre="Ação" data-rating="14 anos"><a href="https://www.youtube.com/watch?v=F72pcCd7hv8"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX7oaJhUihKA3Dm61NHrcFJ3on-aKXFyAnjGRsE2C0Pjdg48MdT2mBlWY15ZBxf3L1DKA&amp;usqp=CAU&quot; alt=" cartaz="" do="" filme="" 2"=""></a></td>
                                 <td data-genre="Comédia" data-rating="12 anos"><a href="https://www.youtube.com/watch?v=Ql48PmDLsuw"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX7oaJhUihKA3Dm61NHrcFJ3on-aKXFyAnjGRsE2C0Pjdg48MdT2mBlWY15ZBxf3L1DKA&amp;usqp=CAU&quot; alt=" cartaz="" do="" filme="" 3"=""></a></td>
                                 </tr>
                                 <tr>
                                 <td>14h</td>
                                 <td data-genre="Aventura" data-rating="10 anos"><a href="https://www.youtube.com/watch?v=1PQecSklHVY"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX7oaJhUihKA3Dm61NHrcFJ3on-aKXFyAnjGRsE2C0Pjdg48MdT2mBlWY15ZBxf3L1DKA&amp;usqp=CAU&quot; alt=" cartaz="" do="" filme="" 4"=""></a></td>
                                 <td data-genre="Drama" data-rating="16 anos"><a href="https://www.youtube.com/watch?v=dFV-UKVLieE"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX7oaJhUihKA3Dm61NHrcFJ3on-aKXFyAnjGRsE2C0Pjdg48MdT2mBlWY15ZBxf3L1DKA&amp;usqp=CAU&quot; alt=" cartaz="" do="" filme="" 5"=""></a></td>
                                 <td data-genre="Ficção científica" data-rating="12 anos"><a href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX7oaJhUihKA3Dm61NHrcFJ3on-aKXFyAnjGRsE2C0Pjdg48MdT2mBlWY15ZBxf3L1DKA&amp;usqp=CAU"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX7oaJhUihKA3Dm61NHrcFJ3on-aKXFyAnjGRsE2C0Pjdg48MdT2mBlWY15ZBxf3L1DKA&amp;usqp=CAU&quot; alt=" cartaz="" do="" filme="" 6"=""></a></td>
                                 </tr>
                                 <tr>
                                 <td>18h</td>
                                 <td data-genre="Terror" data-rating="18 anos"><a href="https://www.youtube.com/watch?v=4zStDzovuz8&amp;list=PLqEMUdJISqdPZ_QZCNU7DJ-cI_xwJd2mm&amp;pp=iAQB"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX7oaJhUihKA3Dm61NHrcFJ3on-aKXFyAnjGRsE2C0Pjdg48MdT2mBlWY15ZBxf3L1DKA&amp;usqp=CAU&quot; alt=" cartaz="" do="" filme="" 7"=""></a></td>
                                 <td data-genre="Comédia" data-rating="14 anos"><a href="https://www.youtube.com/watch?v=kmFBNV_LCk4"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX7oaJhUihKA3Dm61NHrcFJ3on-aKXFyAnjGRsE2C0Pjdg48MdT2mBlWY15ZBxf3L1DKA&amp;usqp=CAU&quot; alt=" cartaz="" do="" filme="" 8"=""></a></td>
                                 <td data-genre="Drama" data-rating="16 anos"><a href="https://www.youtube.com/watch?v=OS4tQxJjXmo"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX7oaJhUihKA3Dm61NHrcFJ3on-aKXFyAnjGRsE2C0Pjdg48MdT2mBlWY15ZBxf3L1DKA&amp;usqp=CAU&quot; alt=" cartaz="" do="" filme="" 9"=""></a></td>
                                 </tr>
                                 </tbody></table>
                                 
                                 </body></html>
