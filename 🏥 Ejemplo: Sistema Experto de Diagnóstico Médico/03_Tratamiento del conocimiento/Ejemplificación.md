# 🔹 3. Tratamiento del Conocimiento

📌 Qué ocurre aquí:
El Motor de Inferencia compara las reglas de la base de conocimiento con los hechos de la base de datos.
Aquí también entran en juego:
- El Subsistema de control de coherencia, que evita contradicciones.
- El Subsistema de explicación, que justifica la decisión.

📌 Ejemplo aplicado:
- El motor de inferencia recibe los hechos del paciente Juan: fiebre = 39°C, tos con flemas, dificultad respiratoria y dolor torácico.
- Aplica la Regla 1:
    - Condiciones cumplidas: Fiebre > 38.5°C ✅, tos con flemas ✅, dificultad respiratoria ✅, dolor torácico ✅.
    - Conclusión: “Probable neumonía”.
- Además, el motor de inferencia detecta que no hay contradicciones en los datos (coherencia garantizada).
- El subsistema de explicación genera una justificación para el médico:
    - “El diagnóstico de neumonía se sugiere porque el paciente presenta fiebre de 39°C, tos con flemas, dificultad respiratoria y dolor torácico, que cumplen con la Regla 1 del conocimiento médico almacenado”.

## 👉 Resultado: 
El sistema llega a una conclusión diagnóstica razonada y con una explicación clara.

![alt text](image.png)