# automate_start_stop_ec2
Script em Pyhton para Ligar e Desligar instâncias EC2 AWS


Para automatizar suas instâncias AWS para ligar e desligar em horários especificos podemos usar o AWS Lambda.

Lá você cria a função em python e usar os scripts que estão aqui no repositório.

Após realizar a configuração no AWS Lambda você precisa criar uma Regra no Painel do Cloudwatch, é lá que você vai definir a hora de Start e Stop da função criada.

