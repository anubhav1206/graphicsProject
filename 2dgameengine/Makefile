build:
	g++ -w -std=c++14 -Wfatal-errors \
	./src/*.cpp \
	-o game \
	-I"./lib/lua" \
	-L"./lib/lua" \
	-llua5.3 \
	-lSDL2 \
	-lSDL2main \
	-lSDL2_image \
	-lSDL2_ttf \
	-lSDL2_mixer;

clean:
	rm ./game;

run:
	./game;