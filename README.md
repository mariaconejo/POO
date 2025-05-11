# POO
Identificar 5 Entidades que ustedes gusten de ellas se debe obtener una sola clase padre o superclase. Lunes 14 de abril

## Clase Padre: Game

 atributos: Name, Position, State, TypeCharacter

 metodos: Moving(), Interaction(), ShowInformation()


## Clase Hija: Player hereda de Game

 atributos: Propios: Experience, Level, Inventory ,HitPointsPlayer Padre: Name, Positio, State, TypeCharacter

 metodos:   Propios: AttackEnemy(), Defend(), UseObject() Padre: Moving(), Interaction(), ShowInformation()


## Clase Hija: Enemy hereda de Game

atributos: Propios: KindOfAttack, DifficultyLevel, SpawningArea ,HitPointsEnemy Padre: Name, Position; State, TypeCharacter

metodos:   Propios: AttackPlayer(), Patrol(), RunAway() Padre: Moving(), Interaction(), ShowInformation()


## Class Weapon 

atributos: ObjectType, Value, Durability ,Location

metodos: ActiveObject(), CollectObject(), BreakObject()


## Class Map 

 atributos: MapSize, MapType, DifficultyMapLevel 

 metodos: LoadMap(), FinishMap(), TriggerEvents()
