class Empresa {
  String nome = "EASY";

  String GetNome() {
    return this.nome;
  }

  void SetNome(String nome) {
    this.nome = nome;
  }
}

void main() {
  Empresa empresa = Empresa();
  print(empresa.nome);
  empresa.SetNome("GG");
  empresa.GetNome();
  print(empresa.nome);
}
