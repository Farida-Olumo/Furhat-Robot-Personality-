from furhat_remote_api import FurhatRemoteAPI
from emotions import EmotionGenerator

from friendly import play_friendly
from angry import play_angry
from shy import play_shy
from neutral import play_neutral

def main():
    furhat = FurhatRemoteAPI("localhost")
    furhat.set_voice(name='Matthew')
    emotion_generator = EmotionGenerator()

    play_friendly(furhat, emotion_generator)
    play_angry(furhat, emotion_generator)
    play_shy(furhat, emotion_generator)
    play_neutral(furhat, emotion_generator)

    print("Experiment Complete.")

if __name__ == "__main__":
    main()
