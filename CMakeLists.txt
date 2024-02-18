cmake_minimum_required(VERSION 3.27)
project(MuminCoin)

set(CMAKE_CXX_STANDARD 23)

add_executable(MuminCoin main.cpp
        Engine/Headers/Util.h
        Engine/Util.cpp
        Engine/Headers/Uint.h
        Engine/Headers/UIBase.h
        Engine/UIBase.cpp
        Engine/Headers/UI.h
        Engine/UI.cpp
        Engine/Headers/Crypto/Sha.h
        Engine/Crypto/Sha.cpp
        Engine/Headers/Serialize.h
        Engine/Headers/Script.h
        Engine/Script.cpp
        Engine/Headers/Net/Net.h
        Engine/Net/Net.cpp
        Engine/Headers/Market.h
        Engine/Market.cpp
        Engine/Headers/Main.h
        Engine/Headers/Data/DataBase.h
        Engine/DataBase.cpp
        Engine/Headers/Header.h
        Engine/Headers/Key.h
        Engine/Headers/Net/Irc.h
        Engine/Net/Irc.cpp
        Engine/Data/DataBase.cpp
        Engine/Headers/Data/BigNum.h
        Engine/Headers/Base.h)
