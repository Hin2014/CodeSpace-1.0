# CodeSpace-1.0
# DexPixel - Mini programa en Python 🎮

def banner():
    print("=" * 40)
    print("🚀 PROYECTO: DEXPIXEL SYSTEM")
    print("🎮 Estado: ONLINE")
    print("=" * 40)

def main():
    banner()

    print("\n👾 Bienvenido al sistema DexPixel")
    
    nombre = input("Introduce tu nombre: ").strip()

    if not nombre:
        nombre = "dexpixel"

    print(f"\n✨ Acceso concedido, {nombre}")
    print("🧠 Iniciando módulo de experiencia...")
    
    nivel = 1
    exp = 0

    print(f"\n📊 Estado inicial:")
    print(f"- Nivel: {nivel}")
    print(f"- EXP: {exp}")

    print("\n🎯 Misión: Sigue aprendiendo Python")

    accion = input("\n¿Quieres ganar experiencia? (si/no): ").lower()

    if accion == "si":
        exp += 50
        nivel += 1
        print("\n⚡ ¡EXP ganada!")
    else:
        print("\n😐 Sin cambios en tu progreso")

    print(f"\n📊 Estado final:")
    print(f"- Nivel: {nivel}")
    print(f"- EXP: {exp}")

    print("\n👋 Fin del programa DexPixel")

if __name__ == "__main__":
    main()
