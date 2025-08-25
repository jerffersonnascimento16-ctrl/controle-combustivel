# controle-combustivel
Programa em Python que calcula o consumo médio de combustível (km/L).

combustivel = float(input("Quantos listros de combustivel voçê colocou no seu carro ? "))
quilometros = float(input("Quantos quilomentros voçê roudou ? "))
resultado = quilometros / combustivel 
print(f"Seu carro fez em média {resultado:.2f} kms por litros")
