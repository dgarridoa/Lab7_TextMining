# Objetivos

### 1. Aprender como representar un documento como un vector.


### 2. Conocer algunas aplicaciones de textmining tales como:

    2.1 Categorización de noticias.

    2.2 Recuperación de información.

    2.3 Descubrimiento de tópicos.


# Introducción

#### ¿Por qué los datos no estructurados son tan importantes?

Las empresas están tomando decisiones solo con el 20% de la información a la que tienen acceso, ya que el 80% de su información es no estructurada y no se puede utilizar completamente. Las compañías han tratado de darle sentido a los datos no estructurados por años, pero solo un 78% afirma que tienen poca o nula información de sus datos no estructurados.

http://fredrikstenbeck.com/unstructured-data-important/

Fuentes de datos no estructurados en las empresas:
1. Medios de comunicación social. Ej: mención de una compañía o un producto en redes sociales.
2. Fuentes internas. Ej: Presentaciones, material de marketing y ventas, informes, correo electrónico, etc.
3. Contenido generado por el cliente. Ej: Comentarios en línea, historial de navegación, correos electrónicos a un equipo de soporte e incluso llamadas telefónicas al servicio al cliente.

#### ¿Cómo trabajamos con datos no estructurados?

**Embedding**: Llevar datos a una representación númerica. Los modelos trabajan con representaciones númericas!.
Además, con vectores tenemos nociones de distancia y podemos calcular similitud (o disimilitud) entre vectores.

En *text mining* existen dos tipos de *Embedding*, basados en frecuencia y en predicción.

Algunas *keywords*:

1. **Documento (D)**: se refiere a una observación de tipo texto. Ej: comentario, relato, email, etc.
2. **Corpus (C)**: colección de documentos, corresponde al conjunto de datos.
3. **Vocabulario (V)**: corresponde a un conjunto de términos (tokens únicos normalizados) dentro del corpus que sobrevivieron a un procesamiento.
4. **Tokenization**: dividir el texto en entidades significativa llamadas tokens, si cada token es una palabra se habla de unigrams, si cada token son pares de palabras se habla de bigrams, tres palabras son trigrams, así hasta n-grams. En términos más computines es pasar de un string a una lista de strings.
Ejemplo de unigrams:

*'Buenos días estudiantes buenos' = ['Buenos', 'diás', 'estudiantes', 'buenos']*


## Requisitos

```python
- python                    3.7.3
- numpy                     1.16.4
- pandas                    0.24.2
- matplotlib                3.1.0
- scikit-learn              0.21.2
- numba                     0.44.1
- joblib                    0.13.2
- gensim                    3.4.0
- nltk                      3.4.4
- spacy                     2.1.8
- pyemd                     0.5.1
- pyldavis                  2.1.2
```
