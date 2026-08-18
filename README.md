Recurrent Neural Networks (RNNs) process sequential data by maintaining a hidden state that carries information across time steps, making them well suited to text data. Standard RNNs suffer from vanishing gradients over long sequences; Long Short-Term Memory (LSTM) networks address this using gated cells that regulate the flow of information, allowing the network to retain long-range dependencies.
A typical NLP pipeline for sentiment analysis involves:
• Tokenization: converting raw text into integer sequences representing word indices.
• Padding: making all sequences a uniform length so they can be batched.
• Embedding: mapping each word index to a dense vector that captures semantic meaning.
• Sequence Modelling: passing embedded sequences through an LSTM to capture contextual dependencies.
Evaluation: since class distributions and error costs may be uneven, precision, recall, and F1- score provide a more complete picture than accuracy alone.
