# consumo_agua 🚰
# Inserindo variáveis
imovel = input("Digite o tipo de imóvel (comercial, casa ou apartamento): ").lower()
consumo = float(input("Digite o consumo mensal de água em m3: "))
# Determinando valores para as variáveis e discriminando
if imovel == "comercial"🏪:
    print("Tarifa comercial aplicada – consulte o plano corporativo.")
elif imovel == "apartamento"🏙️ and consumo < 10:
    print("Consumo econômico  excelente controle de água!")
elif (imovel == "apartamento" or imovel == "casa"🏠) and consumo <= 25:
    print("Consumo moderado - dentro do padrão residencial.")
else:
    print("Consumo excessivo - adote medidas de economia e verifique vazamentos.")
