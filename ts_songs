import random

musicas = [
    {"nomemusica": "Love Story", "album": "Fearless", "signo": "áries"},
    {"nomemusica": "Shake It Off", "album": "1989", "signo": "touro"},
    {"nomemusica": "Blank Space", "album": "1989", "signo": "gêmeos"},
    {"nomemusica": "Bad Blood", "album": "1989", "signo": "câncer"},
    {"nomemusica": "Style", "album": "1989", "signo": "leão"},
    {"nomemusica": "Delicate", "album": "Reputation", "signo": "virgem"},
    {"nomemusica": "End Game", "album": "Reputation", "signo": "libra"},
    {"nomemusica": "I Knew You Were Trouble", "album": "Red", "signo": "escorpião"},
    {"nomemusica": "22", "album": "Red", "signo": "sagitário"},
    {"nomemusica": "We Are Never Ever Getting Back Together", "album": "Red", "signo": "capricórnio"},
    {"nomemusica": "Wildest Dreams", "album": "1989", "signo": "aquário"},
    {"nomemusica": "All Too Well", "album": "Red", "signo": "peixes"},
    {"nomemusica": "Red", "album": "Red", "signo": "áries"},
    {"nomemusica": "Mean", "album": "Speak Now", "signo": "touro"},
    {"nomemusica": "Mine", "album": "Speak Now", "signo": "gêmeos"},
    {"nomemusica": "Fearless", "album": "Fearless", "signo": "câncer"},
    {"nomemusica": "Speak Now", "album": "Speak Now", "signo": "leão"},
    {"nomemusica": "Enchanted", "album": "Speak Now", "signo": "virgem"},
    {"nomemusica": "Back to December", "album": "Speak Now", "signo": "libra"},
    {"nomemusica": "Our Song", "album": "Taylor Swift", "signo": "escorpião"},
    {"nomemusica": "Teardrops on My Guitar", "album": "Taylor Swift", "signo": "sagitário"},
    {"nomemusica": "The Story of Us", "album": "Speak Now", "signo": "capricórnio"},
    {"nomemusica": "Sparks Fly", "album": "Speak Now", "signo": "aquário"},
    {"nomemusica": "Long Live", "album": "Speak Now", "signo": "peixes"},
    {"nomemusica": "New Romantics", "album": "1989", "signo": "áries"},
    {"nomemusica": "State of Grace", "album": "Red", "signo": "touro"},
    {"nomemusica": "Holy Ground", "album": "Red", "signo": "gêmeos"},
    {"nomemusica": "Everything Has Changed", "album": "Red", "signo": "câncer"},
    {"nomemusica": "Treacherous", "album": "Red", "signo": "leão"},
    {"nomemusica": "Ours", "album": "Speak Now", "signo": "virgem"},
    {"nomemusica": "I Don't Wanna Live Forever", "album": "Colaboração", "signo": "libra"},
    {"nomemusica": "Safe & Sound", "album": "Trilha Sonora", "signo": "escorpião"},
    {"nomemusica": "Begin Again", "album": "Red", "signo": "sagitário"},
    {"nomemusica": "Out of the Woods", "album": "1989", "signo": "capricórnio"},
    {"nomemusica": "Welcome to New York", "album": "1989", "signo": "aquário"},
    {"nomemusica": "Getaway Car", "album": "Reputation", "signo": "peixes"},
    {"nomemusica": "Don't Blame Me", "album": "Reputation", "signo": "áries"},
    {"nomemusica": "This Love", "album": "1989", "signo": "touro"},
    {"nomemusica": "The Archer", "album": "Lover", "signo": "gêmeos"},
    {"nomemusica": "...Ready For It?", "album": "Reputation", "signo": "câncer"},
    {"nomemusica": "Babe", "album": "Colaboração", "signo": "leão"},
    {"nomemusica": "White Horse", "album": "Fearless", "signo": "virgem"},
    {"nomemusica": "Should've Said No", "album": "Taylor Swift", "signo": "libra"},
    {"nomemusica": "Change", "album": "Fearless", "signo": "escorpião"},
    {"nomemusica": "Call It What You Want", "album": "Reputation", "signo": "sagitário"},
    {"nomemusica": "Back To December", "album": "Speak Now", "signo": "capricórnio"},
    {"nomemusica": "Our Song", "album": "Taylor Swift", "signo": "aquário"},
    {"nomemusica": "Teardrops on My Guitar", "album": "Taylor Swift", "signo": "peixes"},
    {"nomemusica": "The Story of Us", "album": "Speak Now", "signo": "áries"},
    {"nomemusica": "Sparks Fly", "album": "Speak Now", "signo": "touro"}

]

def obter_musica_por_signo(signo_usuario):
    musicas_por_signo = [musica for musica in musicas if musica["signo"] == signo_usuario]

    if musicas_por_signo:
        musica_aleatoria = random.choice(musicas_por_signo)
        nome_musica = musica_aleatoria["nomemusica"]
        album = musica_aleatoria["album"]
        return f'musica da loirinha sugerida pra vc: {nome_musica} - {album}'
    else:
        return f'nenhuma musica encontrada para o signo {signo_usuario.capitalize()}.'


signo_usuario = input("Qual é o seu signo? ").lower()


resultado = obter_musica_por_signo(signo_usuario)
print(resultado)
