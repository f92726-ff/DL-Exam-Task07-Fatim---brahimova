# Task 2: MNIST Classification with Data Augmentation

**Student:** Fatima İbrahimova 
**ID:** S207
**Seed:** 20240207 

## Presentation
[View Presentation Slides](https://docs.google.com/presentation/d/1-ZE8KgoNyclaAR2mOWNVlJBoYbk5qjvUBKZPqTuh5Tg/edit?slide=id.g3b367aceeb9_2_95#slide=id.g3b367aceeb9_2_95)

## Dataset
- **Name:** MNIST (28×28 grayscale handwritten digits)
- **Classes:** 10 (digits 0-9)
- **Training samples:** 60,000
- **Test samples:** 10,000

## Model Architecture
- **Type:** CNN 
- **Convolutional layers:** 2 
- **Fully connected layers:** 2 
- **Total parameters:** 421,642

## Training Comparison

### Version 1 (Without Augmentation):
- **Learning rate:** 0.001
- **Batch size:** 64
- **Optimizer:** Adam
- **Test accuracy:** 99.14%

  ### Version 2 (With Augmentation):
- **Learning rate:** 0.001
- **Batch size:** 64
- **Optimizer:** Adam
- **Test accuracy:** 99.34% 

### Best Result
- **Best version:** Version 1
- **Final test accuracy:** 99.34%
- **Target accuracy:** 90.00%
- **Status:** ✓ Achieved

## Analysis
- **Best performing class:** 1 
- **Worst performing class:** 5
- **Key observations:** 
  1. Hər iki model eyni learning rate (0.001) ilə təlim olunub, buna görə performans fərqi augmentasiya səbəbindən yaranır.
  2. With Augmentation modeli 99.34%, Without Augmentation modeli isə 99.14% dəqiqlik əldə etmişdir. Fərq nisbətən kiçik olsa da (0.20%), data augmentation tətbiq edilən model daha yüksək dəqiqlik göstərdiyi üçün daha yaxşı performansa malik model hesab olunur.
