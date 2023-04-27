#  EJECUTE EL CODIGO EN SU COMPILADOR FAVORITE


# Definir la cantidad de puntos de historia de usuario completados en un sprint
puntos_completados = 50

# Definir la duración del sprint en días
duracion_sprint = 10

# Definir la dedicación del equipo de desarrollo en porcentaje
dedicacion = 0.15

# Calcular la cantidad de días de trabajo efectivo en el sprint
dias_trabajo_efectivo = duracion_sprint * (1 - dedicacion)

# Calcular la velocidad del equipo de desarrollo
velocidad = puntos_completados / dias_trabajo_efectivo

# Imprimir la velocidad del equipo de desarrollo
print("La velocidad del equipo de desarrollo es:", velocidad, "puntos de historia de usuario por día")
