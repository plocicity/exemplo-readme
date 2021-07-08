{
  chassis: "************21376",
  model: "I/HYUNDAI I30 2.0",
  color: "PRETA",
  brand: "I/HYUNDAI I30 2.0",
  date: "20/05/2016 às 15:34:51",
  return_message: "Sem erros.",
  city: "SAO PAULO",
  return_code: "0",
  state: "SP",
  model_year: "2011",
  plate: "AFT0017",
  year: "2010",
  status_code: "0",
  status_message: "Sem restrição"

var carro = {
marca: "Ford",
modelo: "Ka",
getDetalhes: function () {
return this.marca + ' - ' + this.modelo;
    }
}

carro.modelo = "Novo Ka";
alert(carro.getDetalhes());


function Carro()
{
  var Marca = "Sem marca";
  var Modelo = "Sem modelo";
  this.SetMarca = SetMarca;
  this.SetModelo = SetModelo;
  this.ShowMarca = DisplayMarca;
  this.ShowModelo = DisplayModelo;

  function DisplayMarca(){
    alert(Marca);
  }

  function DisplayModelo(){
    alert(Modelo);
  }

  function SetMarca(_marca) {
    Marca = _marca;
  }

  function SetModelo(_modelo) {
      Modelo = _modelo;
  }

  }
  var carro = new Carro();
  carro.SetMarca("Ford");
  carro.SetModelo("Ka");
  carro.ShowMarca();
  carro.ShowModelo();
  
</script>
</head>
</body>
</html>





{
  return_code: "0",
  model: "I/MMC L200 4X4",
  model_year: "1993",
  state: "SP",
  status_message: "Roubo/Furto",
  year: "1992",
  color: "PRETA",
  status_code: "1",
  plate: "FFF0012",
  date: "20/05/2016 às 15:54:21",
  chassis: "************01561",
  brand: "I/MMC L200 4X4",
  return_message: "Sem erros.",
  city: "SAO PAULO"
}

{
  chassis: null,
  model: null,
  color: null,
  brand: null,
  date: null,
  return_message: "Veículo não encontrado.",
  city: null,
  return_code: "3",
  state: null,
  model_year: null,
  plate: null,
  year: null,
  status_code: null,
  status_message: null
}



<a href=” produtos.php?tipo=carro&modelo=palio&cor=verde”>Pálio Verde</a>

<form  name="form1" id="form1" method="GET"> 
    Tipo: <input type="text" name="tipo" id="tipo" /><br/>

    Modelo: <input type="text" name="modelo" id="modelo" /><br/>

    Cor: <input type="text" name="cor" id="cor" /><br/>

    <input name="gravar" type="submit" id="gravar" value="ENVIAR" />

</form>

echo $_GET[“tipo”];
echo $_GET[“modelo”];

echo $_GET[“cor”];
