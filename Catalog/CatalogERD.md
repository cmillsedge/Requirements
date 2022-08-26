```mermaid
erDiagram
    OUTLINE_PARAMETER }|--|| PARAMETER_TYPE : describes
    PARAMETER_TYPE ||--|| DATA_TYPE : filter_behaviour
    OUTLINE_PARAMETER ||--|{ PARAMETER_ROLE: etl_behaviour
    OUTLINE_PARAMETER ||--|{ LOOKUP: controls_vocabulary
    LOOKUP }|--|| DATA_CONCEPT: "categorizes"
    PARAMETER_TYPE }|--|| DATA_CONCEPT: "categorizes?" 
```