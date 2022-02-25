class Aeroporto {
  String nome = "BH";
  String cidade = "SP";

  String GetNome() {
    return nome;
  }

  void SetNome(String nome) {
    this.nome = nome;
  }

  void GetCidade() {
    this.cidade;
  }

  void SetCidade(String cidade) {
    this.cidade = cidade;
  }
}

void main() {
  Aeroporto aeroporto = Aeroporto();
  aeroporto.GetNome();
  print(aeroporto.nome);
  aeroporto.SetNome("Aeroporto da pampulha");
  print(aeroporto.nome);

  aeroporto.GetCidade();
  print(aeroporto.cidade);

  aeroporto.SetCidade("Aeroporto de guarulhos");
  print(aeroporto.cidade);
}
