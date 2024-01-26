# 42_libft
Librería que contiene funciones básicas (y no tan básicas) de C para utilizar en otros proyectos más complejos.

## Primera parte
  Reproducir el comportamiento de funciones ya existentes en la librería libc:
  - ft_strlen
    -- Calcular la longitud de un string
  - ft_isascii
    -- Verificar si un caracter es ascii
  - ft_isdigit
    -- Verificar si un caracter es dígito
  - ft_isalpha
    -- Verificar si un caracter es alfabético
  - ft_isprint
    -- Verificar si un caracter es imprimible
  - ft_isalnum
    -- Verificar si un caracter es alfanumérico
  - ft_tolower
    -- Convertir un caracter mayúscula a minúscula
  - ft_toupper
    -- Convertir un caracter minúscula a mayúscula
  - ft_strlcpy
    -- Copiar n posiciones de un string
  - ft_bzero
    -- Establecer a cero los primeros n bytes de un bloque de memoria
  - ft_strncmp
    -- Comparar dos strings los primeros n caracteres
  - ft_memset
    -- Establecer a un caracter concreto los primeros n bytes de un bloque de memoria
  - ft_memcpy
    -- Copiar un bloque de memoria de un origen a un destino n bytes
  - ft_atoi
    -- Convertir un ascii a interger
  - ft_memchar
    -- Buscar la primera aparición de un byte específico en un bloque de memoria
  - ft_memmove
    -- Copiar un bloque de memoria de un origen a un destino n bytes teniendo en cuenta posibles solapamientos
  - ft_memcmp
    -- Comparar dos bloques de memoria durante n bytes
  - ft_strchr
    -- Buscar la primera aparición de un carácter específico en una string
  - ft_strrchr
    -- Buscar la última aparición de un carácter específico en una string
  - ft_strnstr
    -- Buscar la primera aparición de una subcadena en otra cadena los primeros n caracteres
  - ft_calloc
    -- Reservar bloque de memoria y restablecerlo a cero
  - ft_strdup
    -- Duplicar un string
  
## Segunda parte
  Reproducir el comportamiento de funciones que no existen pero que son útiles de cara a proyectos más complejos:
  - ft_substr
    -- Extraer un substring de un string
  - ft_putstr_fd
    -- Escribir una string en un fd (file descriptor) concreto
  - ft_putchar_fd
    -- Escribir un caracter en un fd (file descriptor) concreto
  - ft_putendl_fd
    -- Escribir un string seguido de un salto de línea en  un fd (file descriptor) concreto
  - ft_putnbr_fd
    -- Escribir un número en un fd (file descriptor) concreto
  - ft_strjoin
    -- Cocatenar dos strings
  - ft_strtrim
    -- Trimmear (cortar por delante o por detrás) una string
  - ft_split
    -- Dividir un string en substrings separados por un caracter n
  - ft_itoa
    -- Convertir int a una cadena de caracteres
  - ft_strmapi
    -- Aplicar una función a cada carácter de un string en un nuevo string
  - ft_striteri
    -- Aplicar una función a cada carácter de un string
    
## Bonus
  Funciones de manipulación de lista enlazadas:
  - ft_lstnew
    -- Crear un nuevo nodo
  - ft_lstadd_front
    -- Colocar un nodo el primero
  - ft_lstadd_back
    -- Colocar un nodo el último
  - ft_lstsize
    -- Medir la longitud de una lista
  - ft_lstlast
    -- Devuelve un puntero al último nodo de una lista
  - ft_lstdelone
    -- Eliminar un nodo concreto y liberar la memoria del contenido
  - ft_lstclear
    -- Eliminar todos los nodos y liberar la memoria tanto de los nodos como de sus contenidos
  - ft_lstiter
    -- Aplicar una función a cada nodo de una lista
  - ft_lstmap
    -- Crear una nueva lista aplicando una función a cada nodo de la lista original
