# Basic Machin Learning



### What is ML?

- Limitations of explicit programming
  - span filter: many rules
  - Automatic driving: too many rules
- MAchine learning: "Field of study that gives computers the ability to learn without being explicitly programmed"



### Supervies Learning vs Unsupervised Learning

- Supervised Learning:
  - Learning with labeled examples => training set
- Unsupervised Learning:
  - Google news groupting
  - word clustering



### Supervised Learning

- Most common problem type in ML
  - Image labeling: learning from tagged images
  - Email spam filter: learning from labeled email
  - Predicting exam score: learning from previous exam score and time spent



### Training data set



### Types of supervised learning

- predicting final exam score based on time spent

  - regression

  | x(hours) | y(scores) |
  | :------: | :-------: |
  |    10    |    90     |
  |    9     |    80     |
  |    3     |    50     |
  |    2     |    30     |

- Pass/ non-pass based on time spent

  - binary classification

    | x(hours) | y(pass/fail) |
    | :------: | :----------: |
    |    10    |      P       |
    |    9     |      P       |
    |    3     |      F       |
    |    2     |      F       |

- Letter grade( A, B, C, D, and F) based of time spent

  - multi-label classification

    | x(hours) | y(grade) |
    | :------: | :------: |
    |    10    |    A     |
    |    9     |    B     |
    |    3     |    D     |
    |    2     |    F     |