require_once "JoaoPedro.php";

class SobreMim extends Desenvolvedor {
  public $nome = "Joao P. Soares";
  public $area = "Desenvolvedor de Software";
  public $contato = [
      "joaopedroszr@gmail.com",
      "instagram.com/joaotiff",
      "cvjoaopedro.netlify.app"
    ];
  public $trabalho = "GrupoGet";
  public $local = "Belo Horizonte/MG";
}

class Skills extends Desenvolvedor {
  public $linguagens = [
      "C#",
      "java",
      "JavaScript",
      "PhP",
      "SQL"
    ];
  public $bibliotecas = ["JQuery"];
  public $frameworks = [
      "Laravel",
      "ReactJS",
    ];
}
