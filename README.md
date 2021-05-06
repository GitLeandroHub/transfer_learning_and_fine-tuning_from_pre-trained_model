Deep Learning: Aprendizado por Transferência e Ajuste Fino à partir de um modelo pré-treinado

Para elaborar esse Jupyter Notebook foram usadas as seguintes ferramentas:
    - Python 3
    - Anaconda Navigator
    - tf-nightly (Tensor Flow), criado à partir de um novo canal(linha de comando) no Anaconda.
    - Modelos pré-treinados MobileNet V2 (google)
    - Tutorial transfer_learning do TensorFlow.org

O arquivo "transfer_learning_and_fine-tuning_from_pre-trained_model.ipynb" classifica imagens de cães e gatos utilizando aprendizagem por transferência de um modelo pré-treinado. Modelo esse salvo anteriormente em um grande conjunto de dados, servindo efetivamente como um modelo genérico do mundo visual. Nesse caso, não foi necessário "começar do zero".

zip das imagens: https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip

O modelo básico a ser classificado foi criado a partir de uma instância do MobileNet V2 (desenvolvido no Google), este modelo(MobileNet v2) é pré-treinado no conjunto de dados ImageNet, um grande conjunto de dados (1,4 milhões de imagens e 1000 classes). Essa base de conhecimento ajuda a classificação dos cães e dos gatos do conjunto específico que foi abordado aqui pelo arquivo zip.

https://github.com/GitLeandroHub

No arquivo "deep_learning_transfer.gif" segue uma prévia do resultado final do código em funcionamento.

![](transfer_learning_model.gif)
