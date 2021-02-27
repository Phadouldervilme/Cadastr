# Cadastr
from pysimpleGUI import pysimpleGUI as sg

# Layout
sg.theme('Reddit')
layout = [

    [sg.text('Usuário'),sg.input('key= Usuario')],
    [sg.text ('senha'),sg.input('key= 'senha',password_char='*') ],
    sg.checkbox('Você deseja salvar e seu login?')
    [sg.botton('entrar')]
]
# Janela
janela = sg.window('Tela de login',layout)
# Ler os eventos
while true:
    eventos, valores = janela.read
    if eventos ==sg.WINDOW_CLOSED:
        break
        if eventos == 'entrar':
            if valores['Usuario'] == 'Phadoul' and valores ['Senha']==
            '123456':
            print('Seja Bem-vindo!!')
