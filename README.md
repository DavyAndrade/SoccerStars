# SoccerStars
Um protótipo de um jogo de futebol baseado em turnos e escolha.

import random

# Zonas do Campo
field = ["GA", "MCD", "MC", "MCO", "GA"]


def iniciarPartida():
    print("Iniciando partida...")

def exibirCampo(i):
    print(f"A bola está em {field[i]}")

def chooseAtk(i):
    if i <= 2:
        print("Escolha como prosseguir: ")
        print("1 - Drible")
        print("2 - Passe")
    else:
        print("Escolha como prosseguir: ")
        print("1 - Drible")
        print("2 - Passe")

def menu():
    i = 2
    exibirCampo(i)


iniciarPartida()
menu()
