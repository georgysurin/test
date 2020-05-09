# test
Решение тестового задания. 
Для решения я взял за основу код из https://github.com/davidstap/AttnGAN в котором реализована архитекутра из статьи http://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_AttnGAN_Fine-Grained_Text_CVPR_2018_paper.pdf
И добавил линейный слой после эмбедера в /code/model.py (line 113) (при этом увеличив размероность выходящего вектора из эмбедера)
Как показано в статье http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhu_A_Generative_Adversarial_CVPR_2018_paper.pdf
этот дополнительный слой после эмбедера влияет на подавление шума в текстовых данных.
К сожаления, у меня в доступе сейчас нет необходимых ресурсов, для обучения этой архитектуры с нуля, но код работает. 
Для проверки необходимо скачать данные для датасета birds: https://drive.google.com/file/d/1O_LtUP9sch09QH3s_EBAgLEctBQ5JBSJ/view
http://www.vision.caltech.edu/visipedia/CUB-200-2011.html
и далее следовать инструкции по запуску, как показано в https://github.com/davidstap/AttnGAN
