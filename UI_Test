from guizero import App, Text, TextBox, PushButton

def get_position():
    comment0.value = positionx.value + positiony.value + positionz.value

app = App(title="See through buildings for emergency evacuation", layout="auto")
comment0  = Text(app, text="Welcome to the see-through application", size=40, font="Times New Roman", color="lightblue")

commentx  = Text(app, text="X = ")
positionx = TextBox(app, width=10)

commenty  = Text(app, text="Y = ")
positiony = TextBox(app, width=10,)

commentz  = Text(app, text="Z = ")
positionz = TextBox(app, width=10,)

update_text = PushButton(app, command=get_position, text="Start the sensor")

app.display()
