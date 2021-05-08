var today = new Date();
var days = ['Domingo', 'Lunes', 'Martes', 'Miercoles', 'Jueves', 'Viernes', 'Sabado'];
var moths = ['Enero', 'Febrero', 'Marzo', 'Abril', 'Mayo', 'Junio', 'Julio', 'Agosto', 'Septiembre', 'Octubre', 'Noviembre', 'Diciembre'];

let weekDay = days[today.getDay()]; //Dia de la semana [lunes, martes, ...]
let monthDay = today.getDate(); //Dia del mes [1,2,3,4,....,30]
let month = today.getMonth(); // Mes
let monthName = months[month];
let year = today.getFullYear(); //Año

var fecha = document.getElementById('fecha'); //Obtiene el elemento H1 con ID = fecha
fecha.innerHTML = $(weekDay), $(monthDay) $(monthName); //Agrewgamos Codigo HTML a la variable fecha, se reflejara en el H1
