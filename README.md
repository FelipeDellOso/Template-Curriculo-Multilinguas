# Template-Currículo-Multilínguas

Criei essa base de currículo após sentir a necessidade de uma forma mais prática de alterar o meu currículo, fosse por motivações de atualização, fosse por demandas específicas da vaga em questão. 

Os principais pontos que busquei resolver com este template são:

-centralizar todas as informações relevantes para o meu currículo em um único documento

-facilidade de criar novas versões para envio para diferentes vagas

-facilidade para manter o currículo atualizado em mais de uma língua

A princípio não planejava compartilhá-lo, mas como outras pessoas demonstraram interesse, resolvi subí-lo aqui, assim tornando também possível que outras pessoas possam contribuir.

Instruções gerais de uso:

-Escolher uma ferramenta de compilação de LaTeX. Recomendo o overleaf.com, pois não necessita de download ou instalação, além de ser acessível em qualquer browser.

-LaTeX pode ser um pouco assustador no primeiro momento para quem não está acostumado com alguma linguagem de programação. Nesse caso, recomendo apenas tentar reproduzir os padrões que estão prontos no template, e fazer backups de vez em quando, pois é possível que um erro faça ele deixar de compilar.

-Muitas vezes podemos desejar remover um item do nosso currículo em favor de enfatizar outros de maior relevância para a vaga em questão. Nesse caso, basta comentar fora as línguas que deseja esconder. Para fazer isso, selecione-as e pressione CTRL+/. Faça o mesmo para descomentar quando quiser que algo volte a ser incluído.

-Para adicionar novos campos, siga o padrão dos já existentes. Basta copiá-los e alterar o conteúdo conforme desejar.

Sobre a funcionalidade de multilínguas:

-Esse template não traduz automaticamente o seu currículo, você que precisa preencher todos os campos com as várias versões diferentes. Isso é efeito com o comando \multilanguage. 

-A definição de qual língua será usada para gerar o PDF é dada pela linha "\usepackage[IDIOMA]{optional}", sendo IDIOMA aquele que você deseja usar. Apenas uma dessa linha pode existir sem estar comentada por vez. Descomentando uma e comentando outra, você facilmente consegue gerar o seu currículo em outra língua, usando exatamente a mesma formatação.

-Para escrever um texto que será selecionado em função do idioma escolhido, basta colocá-lo dentro de \multilanguage{TEXTO EM PORTUGUES}{TEXTO EM INGLÊS}, sendo que o primeiro campo das chaves deve conter o seu texto em português, e o segundo em inglês.

-É possível alterar ou adicionar idiomas, mas não me recordo dos detalhes neste momento. Em breve adicionarei essas instruções.

Alguns campos não geram textos diretamente no PDF, mas alteram por exemplo um link ou uma meta informação. Recomendo reler todo o arquivo .tex antes de dar como finalizado. Os principais seguem abaixo:
-pdfauthor e pdftitle
-link do linkedin
-link do e-mail
-link da publicação acadêmica
