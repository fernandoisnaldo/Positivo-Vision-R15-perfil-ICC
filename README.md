# PositivoVR15.icc
Repositório criado com objetivo de disponibilizar um perfil icc para tentar corrigir o balanço de branco de alguns lotes do laptop Positivo Vision R15, que tem um tom mais alaranjado.

O meu calibrador de tela ainda não chegou, então enquanto isso, eu recomendo utilizar o perfil Bluish.icc como alternativa provisória para o balanço de branco, até termos uma solução um pouco melhor.

Link para o Bluish.icc:
https://github.com/OpenICC/xcalib/blob/master/bluish.icc (este perfil não foi gerado por mim e nem foi feito pra este laptop, aguardem atualizações do meu repositório para melhor resultado)

Nenhum perfil de cores publicado neste repositório, tem garantia expressa ou implícita de quem o disponibilizou.

Não há nenhuma promessa no tocante a fazer o laptop ser destinado a qualquer meio de produção audiovisual, pois este laptop não foi feito pra esta finalidade, então caso você trabalhe com isso, compre um laptop feito para isso ou um monitor profissional.

O perfil icc deste repositório não será corrigido e nem atualizado, sendo somente publicado 1 única vez de acordo com as condições específicas do meu laptop. Caso o meu perfil icc não resolva o seu problema, eu recomendo fazer a sua própria calibração ou enviar o produto para a garantia.

*TODO:*
publicar perfil icc


Atualização de 25 de Agosto, após analisar uma imagem que eu criei com as cores vermelho (#ff0000), azul(#00ff00) e verde(#0000ff).
![Imagem RGB](https://github.com/fernandoisnaldo/Projeto-icc-RDS-220/blob/main/rgb.png)

Características observadas no monitor, que independem do perfil de cores utilizados, que são do próprio hardware e que eu mesmo consegui percebi.

  Os subpixels azuis estão corretos e representam de fato a cor azul.
  Os subpixels verdes estão puxados pro verde-limão (ou seja, sensivelmente mais amarelados em comparação com a maioria dos monitores).
  Os subpixels vermelhos estão levemente puxados pra uma cor levemente alaranjada, mas que ainda dá pra chamar de vermelho.

Isso implica que a reprodução de cores pode ser sensivelmente limitada pelos subpixels verdes, puxando naturalmente tons mais amarelados.

Isso não impede uma mudança de balanço de branco, mas implica em questões que são do próprio hardware mesmo.
