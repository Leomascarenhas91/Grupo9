// filtra pelos mesmos níveis e horas disponíveis
Find records where
  Nivel = {{experiencia}}
  and "Carga horaria (h)" <= {{horas_semanais}}
  Dias disponíveis: {{dias_da_semana}}

Return fields:
  Curso,
  "Carga horaria (h)" as carga_horaria,
  turno,
  Nivel