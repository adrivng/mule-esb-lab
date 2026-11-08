GRUPO 1 -> LOGRO 3 - TEMA 9 "DESARROLLADO"


*1.- CALCULADORA USANDO LOGICA CON NEW E INVOKE PARA VALIDAR QUE NO SE PUEDA DIVIDIR POR 0 
TIENE LAS OPERACIONES ARITMETICAS (SOAP) 
POST http://localhost:9090/calculadora?op (SE HIZO LA CONVERSION DE XML A JSON)
{
  "num1": a,
  "num2": b
}
POST http://localhost:9090/calculadora?subtract (SE HIZO LA CONVERSION DE XML A JSON)
{
  "num1": a,
  "num2": b
}
POST http://localhost:9090/calculadora?multiply (SE HIZO LA CONVERSION DE XML A JSON)
{
  "num1": a,
  "num2": b
}
POST http://localhost:9090/calculadora?divide (SE HIZO LA CONVERSION DE XML A JSON)
{
  "num1": a,
  "num2": b
}


*2.- UNIVERSIDADES SOLO UNITED STATES CON VALIDACIÓN MEDIANTE DATAWEAVE* (REST)
GET http://localhost:9090/universidades?pais=United States