# App5
![image](https://user-images.githubusercontent.com/98075789/157200192-c7ed0649-ec82-4560-b384-d939a063e32f.png)
import React from 'react';
import { StyleSheet, Text, View } from 'react-native';

import CountContextProvider from './context/CountContextProvider';
import MainScreen from './components/Mainscreen';
import TopView from './components/TopView';
import Bottom from './components/botoom';
export default function App() {
  return (
   
   <CountContextProvider>
    <MainScreen/>
    <TopView></TopView>
    <Bottom></Bottom>
   </CountContextProvider>
   
  
  );
}
