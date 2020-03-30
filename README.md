# TensorFlowSecond

В рамках данной работы я пытался меняя конфигурацию увидеть, что будет со сверточной сетью, посмотреть на ее поведение и понять результат. Изменяя количество слоев, сверкок в слоях и скорости обучения(lr), я получал различные конфигурации сетей, представленные ниже. 
Выбранные параметры для BATCH_SIZE == 1, NUM_CLASSES == 2.
Конфигурации: 

1. Свёрточная сеть с двумя слоями Conv2D.
    a) Filters == 32. Kernel Size == 3.
    b) Filters == 16. Kernel Size == 3.
    
        lr == 2*10^-9  epochs == 48
    
График метрики точности
![Image alt](https://github.com/deeChyz/TensorFlowSecond/blob/master/ep_cat_ac_7_10_3_123.jpg)


График функции потерь
![Image alt](https://github.com/deeChyz/TensorFlowSecond/blob/master/ep_loss_7_10_3_123.jpg)

График точности на тестовой выборе 
![Image alt](https://github.com/deeChyz/TensorFlowSecond/blob/master/ep_val_cat_acc_7_10_3_123.jpg)
График потерь на тестовой выборке
![Image alt](https://github.com/deeChyz/TensorFlowSecond/blob/master/ep_val_loss_7_10_3_123.jpg)


1. Свёрточная сеть с двумя слоями Conv2D.
    a) Filters == 32. Kernel Size == 3.
    b) Filters == 16. Kernel Size == 3.
		c) Filters == 8. Kernel Size == 3.
    
        lr == 2*10^-9  epochs == 47

Граф метрики точности
![Image alt](https://github.com/deeChyz/TensorFlowSecond/blob/master/ep_cat_acc_9_10_3_122.jpg)


График функции потерь
![Image alt](https://github.com/deeChyz/TensorFlowSecond/blob/master/ep_loss_9_10_3_122.jpg)
