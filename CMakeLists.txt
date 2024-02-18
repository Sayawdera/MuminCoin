cmake_minimum_required(VERSION 3.27)
project(MuminCoin)

set(CMAKE_CXX_STANDARD 23)

add_executable(MuminCoin main.cpp
        Engine/Headers/Util.hxx
        Engine/Util.cpp
        Engine/Headers/Uint.hxx
        Engine/Headers/UIBase.hxx
        Engine/UIBase.cpp
        Engine/Headers/UI.hxx
        Engine/UI.cpp
        Engine/Headers/Crypto/Sha.hxx
        Engine/Crypto/Sha.cpp
        Engine/Headers/Serialize.hxx
        Engine/Headers/Script.hxx
        Engine/Script.cpp
        Engine/Headers/Net/Net.hxx
        Engine/Net/Net.cpp
        Engine/Headers/Market.hxx
        Engine/Market.cpp
        Engine/Headers/Main.hxx
        Engine/Headers/Data/DataBase.hxx
        Engine/DataBase.cpp
        Engine/Headers/Header.hxx
        Engine/Headers/Key.hxx
        Engine/Headers/Net/Irc.hxx
        Engine/Net/Irc.cpp
        Engine/Data/DataBase.cpp
        Engine/Headers/Data/BigNum.hxx
        Engine/Headers/Base.hxx)
