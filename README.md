# Image-Quiz

# Overview
複数のモデルの認識結果をもとに画像を当てるクイズアプリ

# Description
特定の画像に対して、複数のモデル（CNN）で認識をしていき、順に結果を提示します。  
提示された結果をもとに、何の画像かを当てるクイズです。  
10種類のものを分類できるモデルや、2種類しか分類できないモデルなど様々用意しており、  
様々なレベルのモデルを活かしてみました。

# Folder and Files
┏image … クイズで利用する画像の格納用フォルダ。ファイル名は「(ラベル名)_(連番)」。  
┃　┣dog_1.png  
┃　┣ …  
┃  
┣model … 画像分類モデルの格納用フォルダ  
┃　┣model_0_1_2_3_4_5_6_7_8_9.hdf5  
┃　┣ …  
┃  
┣create_model_cifar10.ipynb … 画像分類モデル（CNN）の作成プログラム  
┗image_quiz.ipynb … クイズゲーム用プログラム  

# Capture
![image_quiz](https://user-images.githubusercontent.com/39453720/46592207-7d255200-cafb-11e8-9650-562a330b22be.png)
