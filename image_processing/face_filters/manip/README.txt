Entrambi i file .py sono da lanciare da terminale con il comando 'python2' a precederli, visto che le librerie cv2 e dlib hanno funzioni stabili per python 2.7.

- final.py cattura il video dalla webcam e lo rielabora, applicando il filtro corrispondente indicato sul terminale. Il file .gif viene poi salvato nella cartella 'new', sotto il nome di 'output_panda.gif', 'output_pika.gif', 'output_eyes.gif'. Chiaramente, nel momento in cui viene lanciato di nuovo lo script per lo stesso filtro, il file viene sovrascritto. 

- imageprocessing-filters.py applica i filtri direttamente sullo stream video della webcam.

Entrambi gli script prendono i filtri (immagini png) dalla cartella 'png'.

haarcascade_frontalface_default.xml: in opencv, è un classificatore addestrato che serve per identificare oggetti di un particolare tipo, come per esempio il viso ( frontalface, in questo caso ).

shape_predictor_68_face_landmarks.dat(da scaricare per il corretto funzionamento): rete addestrata per riconoscere i 68 landmarks sul volto analizzato.
