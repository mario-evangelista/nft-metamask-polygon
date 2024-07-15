# nft-metamask-polygon
Criando um NFT na Prática

# Projeto NFT

Este é um projeto de NFT desenvolvido como parte do curso XYZ.

## Descrição

Este projeto cria um contrato inteligente ERC-721 que permite a criação de NFTs na rede Polygon. Os NFTs foram enviados para as carteiras especificadas pelo instrutor.

## Contrato Inteligente

O contrato inteligente foi escrito em Solidity e implantado na rede Polygon usando a MetaMask. O contrato permite que o proprietário (owner) crie novos NFTs.

## Verificação do NFT

Você pode verificar os NFTs criados nas seguintes carteiras:

- **Polygon (OpenSea)**: [0xA9155F5B6FC993A82346a8ff86EFEf513fc4c096](https://opensea.io/accounts/0xA9155F5B6FC993A82346a8ff86EFEf513fc4c096)
- **Uptick**: iaa1ld2ck02x0909lg5tkqwdkfnsnsz7mmg6952jar

## Instruções para Reprodução

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. Abra o [Remix IDE](https://remix.ethereum.org/), importe o contrato inteligente `MyNFT.sol` e compile-o.

3. Conecte sua MetaMask ao Remix e selecione a rede Polygon.

4. Implemente o contrato na rede Polygon e use a função `mint` para criar novos NFTs, enviando-os para a carteira especificada.

## Imagens

### Implantação do Contrato
![Implantação do Contrato](link-para-imagem-implantacao.png)

### Verificação no OpenSea
![Verificação no OpenSea](link-para-imagem-opensea.png)

## Links Úteis

- [MetaMask](https://metamask.io/)
- [Remix IDE](https://remix.ethereum.org/)
- [OpenSea](https://opensea.io/)
- [Polygon (Matic) Documentation](https://docs.polygon.technology/)

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
```

### Passos para adicionar o README.md ao GitHub

1. **Crie o repositório no GitHub**:
   - Vá para [GitHub](https://github.com/new) e crie um novo repositório público.
   - Nomeie o repositório conforme o seu projeto.

2. **Clone o repositório para a sua máquina local**:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

3. **Navegue até o diretório do repositório clonado**:
   ```bash
   cd nome-do-repositorio
   ```

4. **Crie um arquivo README.md e adicione o conteúdo acima**:
   ```bash
   echo "# Projeto NFT" > README.md
   # Cole o conteúdo do exemplo acima no arquivo README.md
   ```

5. **Adicione, commit e envie o arquivo README.md para o repositório remoto**:
   ```bash
   git add README.md
   git commit -m "Adiciona README.md"
   git push origin main
   ```
