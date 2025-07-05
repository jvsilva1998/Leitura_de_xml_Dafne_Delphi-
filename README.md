# 📄 Leitura de XML Dafne (Delphi)

Biblioteca em Delphi para ler e interpretar arquivos XML gerados pela contabilização e integração fiscal da Dafne (SPED, DANFE, NF-e, NFC-e etc.).

---

## 🚀 Funcionalidades

- 📥 Leitura e interpretação de XML de notas fiscais eletrônicas (XML NF-e / NFC-e)
- Extração de dados fiscais: chave, data, emissão, valores, impostos (ICMS, IPI, PIS, COFINS)
- Mapear dados do emitente, destinatário, produtos, transportes, totais e pagamentos
- Conversão automática de dados XML para objetos Delphi (`TDafneNF`, `TDafneItem`, `TDafneImposto`)
- Tratamento de exceções: arquivos inválidos, campos ausentes, encoding

---

## 🧰 Requisitos

- **Delphi** 10.x (Professional, Enterprise ou Community)
- Projetos VCL ou FMX (compatível com ambos)
- Acesso à unidades XML: `Xml.XMLDoc`, `Xml.XMLIntf`, `Xml.Win.msxmldom`
- (Opcional) JSON: `System.JSON`, `REST.Client` para integração com APIs

---

## 📥 Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/jvsilva1998/Leitura_de_xml_Dafne_Delphi.git
   cd Leitura_de_xml_Dafne_Delphi
