SRC=src/*.cpp

pfp: $(SRC)
	g++ -std=c++11 -fopenmp -Wall -Werror -fno-strict-overflow -ftrapv -fwrapv -fno-delete-null-pointer-checks -o fp $(SRC)
#	g++ -Ofast -std=c++11 -fopenmp -o fp $(SRC)

clean:
	rm pfp
