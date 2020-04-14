No curso Deep Learning Framework, Capítulo 10, Programa 02, Redes Neurais Profundas, da Data Science Academy, são comparadas as acurácias dos seguintes frameworks - em grau crescente de complexidade - para prever dígitos escritos à mão do dataset MNIST:

• TensorFlow 2 e Keras (Nível Baixo de Complexidade): 0,9798

• PyTorch (Nível Médio de Complexidade): 0,9650

• NumPy (Nível Alto de Complexidade): 0,9925

A pergunta é que acurácia seria conseguida de maneira menos complexa, ou seja, um framework que se colocasse antes do TensorFlow 2 e Keras. A escolha foi o Deep Learning Studio 2.5, com a vantagem que não ser escrita nenhum linha de código, mas mantendo as variáveis dos programas (epochs = 10, loss = 'categorical_crossentropy', optimizer = 'Adam', metrics = 'accuracy' etc.).
