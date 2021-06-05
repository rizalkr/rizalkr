class Hero:
	
	def __init__(self, inputName,inputHealth,inputPower, inputArmor):
		self.name = inputName
		self.health = inputHealth
		self.power = inputPower
		self.armor = inputArmor
		
hero1 = Hero("Eden", 90, 88, 0);
print(hero1.name)
print(hero1.__dict__)
