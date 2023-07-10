# Denny-s-Bot
Is a little Chat GPT kkkk PQ EU TO FALANDO INGRESS KKAKDAODJAFJ


------------  ---------------

import random
import re

pairs = [
#Lembrando que o Nome do Bot é Denny's BOT
    [
        r"(?i)Qual é a capital da Espanha\??",
        ["A capital da Espanha é Madri."]
    ],
    [
        r"(?i)Qual é o número atômico do hidrogênio\??",
        ["O número atômico do hidrogênio é 1."]
    ],
    [
        r"(?i)Quem pintou 'A Noite Estrelada'\??",
        ["'A Noite Estrelada' foi pintada por Vincent van Gogh."]
    ],
    [
        r"(?i)Qual é o maior lago da América do Sul\??",
        ["O maior lago da América do Sul é o Lago Titicaca."]
    ],
    [
        r"(?i)Qual é o maior deserto do mundo\??",
        ["O maior deserto do mundo é o Deserto do Saara, na África."]
    ],
    [
        r"(?i)Quem foi o criador da Microsoft\??",
        ["Bill Gates é o criador da Microsoft."]
    ],
    [
        r"(?i)Qual é a capital da Itália\??",
        ["A capital da Itália é Roma."]
    ],
    [
        r"(?i)Quem foi o inventor do telefone\??",
        ["Alexander Graham Bell é o inventor do telefone."]
    ],
    [
        r"(?i)Qual é o maior animal marinho\??",
        ["A baleia azul é o maior animal marinho."]
    ],
    [
        r"(?i)Qual é o maior vulcão do mundo\??",
        ["O maior vulcão do mundo é o Mauna Loa, no Havaí."]
    ],
    [
        r"(?i)Quem escreveu 'Odisseia'\??",
        ["'Odisseia' foi escrita por Homero."]
    ],
    [
        r"(?i)Qual é o país com a maior quantidade de medalhas olímpicas\??",
        ["Os Estados Unidos são o país com a maior quantidade de medalhas olímpicas."]
    ],
    [
        r"(?i)Qual é o maior peixe do mundo\??",
        ["O tubarão-baleia é o maior peixe do mundo."]
    ],
    [
        r"(?i)Qual é o símbolo químico do cálcio\??",
        ["O símbolo químico do cálcio é Ca."]
    ],
    [
        r"(?i)Quem foi o primeiro homem a orbitar a Terra\??",
        ["O primeiro homem a orbitar a Terra foi Yuri Gagarin."]
    ],
    [
        r"(?i)Qual é o país com o maior número de ilhas\??",
        ["A Suécia é o país com o maior número de ilhas."]
    ],
    [
        r"(?i)Quem foi o autor de 'Cem Anos de Solidão'\??",
        ["'Cem Anos de Solidão' foi escrito por Gabriel García Márquez."]
    ],
    [
        r"(?i)Qual é o maior parque nacional do mundo\??",
        ["O Parque Nacional de Wrangell-St. Elias, nos Estados Unidos, é considerado o maior parque nacional do mundo."]
    ],
    [
        r"(?i)Qual é a capital da Austrália\??",
        ["A capital da Austrália é Camberra."]
    ],
    [
        r"(?i)Quem escreveu '1984'\??",
        ["'1984' foi escrito por George Orwell."]
    ],
    [
        r"(?i)Qual é o símbolo químico do hidrogênio\??",
        ["O símbolo químico do hidrogênio é H."]
    ],
    [
        r"(?i)Qual é o maior evento esportivo do mundo\??",
        ["A Copa do Mundo de Futebol é considerada o maior evento esportivo do mundo."]
    ],
    [
        r"(?i)Qual é o país com a maior área florestal do mundo\??",
        ["O Brasil é o país com a maior área florestal do mundo."]
    ],
    [
        r"(?i)Qual é o maior rio do mundo\??",
        ["O maior rio do mundo é o Rio Amazonas."]
    ]


]

def chat():
    print("Olá! Inicie o bate-papo digitando uma pergunta ou saudação.")

    while True:
        user_input = input("> ")

        if user_input.lower() == "sair":
            print("Até mais! Tenha um bom dia!")
            break

        response = generate_response(user_input)
        print(response)

def generate_response(user_input):
    for pattern, responses in pairs:
        if re.search(pattern, user_input):
            return random.choice(responses)

    return random.choice(pairs[-1][1])

if __name__ == "__main__":
    chat()



    #As perguntas Disponíveis são:
    "Qual é a capital da Espanha?",
    "Qual é o número atômico do hidrogênio?",
    "Quem pintou 'A Noite Estrelada'?",
    "Qual é o maior lago da América do Sul?",
    "Qual é o maior deserto do mundo?",
    "Quem foi o criador da Microsoft?",
    "Qual é a capital da Itália?",
    "Quem foi o inventor do telefone?",
    "Qual é o maior animal marinho?",
    "Qual é o maior vulcão do mundo?",
    "Quem escreveu 'Odisseia'?",
    "Qual é o país com a maior quantidade de medalhas olímpicas?",
    "Qual é o maior peixe do mundo?",
    "Qual é o símbolo químico do cálcio?",
    "Quem foi o primeiro homem a orbitar a Terra?",
    "Qual é o país com o maior número de ilhas?",
    "Quem foi o autor de 'Cem Anos de Solidão'?",
    "Qual é o maior parque nacional do mundo?",
    "Qual é a capital da Austrália?",
    "Quem escreveu '1984'?",
    "Qual é o símbolo químico do hidrogênio?",
    "Qual é o maior evento esportivo do mundo?",
    "Qual é o país com a maior área florestal do mundo?",
    "Qual é o maior rio do mundo?"

    CASO QUEIRA SAIR DIGITE sair QUE O CHAT BOT (DENNY'S BOT) IRÁ AUTOMÁTICAMENTE SAIR.
