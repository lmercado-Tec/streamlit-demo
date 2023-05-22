import streamlit as st

# Crear un título para la página
st.title("Mi primera aplicación web con Streamlit")

# Añadir texto
st.write("¡Hola! ¡Bienvenido a mi aplicación web!")

# Añadir un botón
if st.button("Haz clic aquí"):
    st.write("¡Acabas de hacer clic en el botón!")

# Añadir una opción de selección
options = ["Opción 1", "Opción 2", "Opción 3"]
selected_option = st.selectbox("Elige una opción", options)
st.write("Seleccionaste la opción:", selected_option)

# Añadir sidebar
st.sidebar.title("Opciones")
sidebar = st.sidebar.selectbox("Selecciona una opción", options)
st.sidebar.write("Seleccionaste la opción:", sidebar)
