## **NOMENCLATURA PARA DESIGNAR IMPORTANCIA DE LOS CASOS DE USO:**
- **A: Alta**

    Son **funciones esenciales** para que el sistema cumpla su propósito. **Su ausencia impide el funcionamiento correcto**, afecta procesos clave o limita funcionalidades críticas. Deben desarrollarse en las primeras etapas del proyecto.

    - **A1**: Caso de uso indispensable. El sistema depende de él para cumplir con su función principal. Su ausencia impide el funcionamiento del sistema.

    - **A2**: Caso de uso crítico. Aunque el sistema puede operar sin él, lo hace de manera limitada o ineficiente. Su ausencia reduce significativamente la utilidad o rendimiento.

    - **A3**: Caso de uso relevante. No impide la operación del sistema, pero es necesario para habilitar funciones clave o estratégicas.

- **M: Media**


    Los casos de uso de **importancia Media (M)** no son críticos para el funcionamiento base del sistema, pero su ausencia puede afectar la usabilidad, fluidez o valor percibido por el usuario.

    - **M1**: El sistema puede funcionar sin este caso de uso, pero su ausencia afecta la experiencia del usuario. Normalmente se desprende de un nivel A1 (Alta prioridad).

    - **M2**: El caso de uso añade funcionalidades deseables o complementarias. Su ausencia no afecta la lógica del negocio, pero sí reduce el atractivo o la eficiencia para el usuario final.

    - **M3**: Funcionalidad utilizada ocasionalmente o en contextos específicos. Es útil para ciertos perfiles de usuario o en escenarios particulares, pero prescindible en el flujo general.

- **B: Baja**

    Los casos de uso de importancia Baja (B) son prescindibles sin afectar la operación del sistema. Se consideran "nice to have".

    - **B1**: Funcionalidad estética, de personalización o conveniencia. Su ausencia no altera la operación ni la experiencia básica del usuario.

    - **B2**: Casos de uso pensados para mantener engagement o diferenciación con respecto a la competencia. No afectan la funcionalidad interna ni la percepción de estabilidad del sistema.

    - **B3**: Funcionalidad experimental, futura o pensada para escalabilidad. No tiene impacto actual y puede ser descartada sin consecuencia alguna.
