set FLASK_APP=stream_imag.py
flask run --host=0.0.0.0


set FLASK_APP=stream_video.py
flask run 
flask run --host=10.0.0.10

http://10.0.0.10:5000/





set FLASK_APP=stream_hum_counter_v1.py
flask run --host=10.0.0.10