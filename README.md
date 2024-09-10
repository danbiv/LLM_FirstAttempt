# LLM_FirstAttempt
From: https://www.youtube.com/watch?v=C9QSpl5nmrY&ab_channel=StatQuestwithJoshStarmer

Decoder-Only Transformer
    * Normal Transformers use one unit to decode the input called the Encoder and a separate unit to generate the output called a Decoder
    * Normal Transformers use two types of Attention during inference "Self-Attention" and "Encoder-Decoder Attention"
    * Normal Transformers use Masked self attention on the outputs only.

    IN CONTRAST:
        * Decoder only transformers have only a single unit for both encoding the input and generating the output
        * Decoder only transformers use a single type of attention: "Masked Self-Attention"
        * Decoder only transformers uses Masked Self Attention on EVERYTHING, input and output.
