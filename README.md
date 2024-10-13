## Projeto Apache Spark com delta lake

Projeto desenvolvido para desmontração do Apache Spark Local gravando arquivos no formato Delta Lake também de forma local.

Projeto python inicializado com o UV (https://github.com/astral-sh/uv).

Comandos utilizados:

```bash copy
uv init
uv venv
uv add pyspark==3.4.0, delta-spark==2.4.0, jupyterlab
```

Os exemplos de código para instanciar o Spark, bem como criar a manipular uma tabela delta, está no arquivo `spark-delta-lake.ipynb`.

Não esqueça de selecionar o seu ambiente virtual (.venv) como Kernel do seu jupyter notebook.

![image](https://github.com/user-attachments/assets/9f89a471-ec02-4944-9178-3f79665f74bf)

Links e referências sobre a compatibilidade da versão do Apache Spark (pyspark) e Delta Lake:

[https://docs.delta.io/latest/releases.html](https://docs.delta.io/latest/releases.html) <br>
[https://mvnrepository.com/artifact/io.delta/delta-spark](https://mvnrepository.com/artifact/io.delta/delta-spark) <br>
[https://github.com/delta-io/delta/releases/](https://github.com/delta-io/delta/releases/)

