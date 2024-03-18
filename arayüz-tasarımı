#!/usr/bin/env python3
# -- coding: utf-8 --

# Form implementation generated from reading ui file 'creatiny.ui'
#
# Created by: PyQt5 UI code generator 5.14.1
#
# WARNING! All changes made in this file will be lost!


from PyQt5 import QtCore, QtGui, QtWidgets
import rospy
from geometry_msgs.msg import Twist
from nav_msgs.msg import Odometry


class Ui_creatiny(object):
    def setupUi(self, creatiny):
        creatiny.setObjectName("creatiny")
        creatiny.resize(1000, 700)
        creatiny.setMinimumSize(QtCore.QSize(1000, 700))
        creatiny.setMaximumSize(QtCore.QSize(1000, 700))
        creatiny.setStyleSheet("background-color: rgb(10, 73, 125);")
        self.centralwidget = QtWidgets.QWidget(creatiny)
        self.centralwidget.setObjectName("centralwidget")
        self.buton_dur = QtWidgets.QPushButton(self.centralwidget)
        self.buton_dur.setGeometry(QtCore.QRect(130, 580, 141, 71))
        self.buton_dur.setMinimumSize(QtCore.QSize(89, 25))
        font = QtGui.QFont()
        font.setFamily("Ubuntu Mono")
        font.setPointSize(16)
        font.setBold(True)
        font.setWeight(75)
        self.buton_dur.setFont(font)
        self.buton_dur.setStyleSheet("background-color: rgb(139, 5, 5);")
        self.buton_dur.setObjectName("buton_dur")
        self.verticalLayoutWidget = QtWidgets.QWidget(self.centralwidget)
        self.verticalLayoutWidget.setGeometry(QtCore.QRect(30, 480, 160, 81))
        self.verticalLayoutWidget.setObjectName("verticalLayoutWidget")
        self.verticalLayout = QtWidgets.QVBoxLayout(self.verticalLayoutWidget)
        self.verticalLayout.setContentsMargins(0, 0, 0, 0)
        self.verticalLayout.setObjectName("verticalLayout")
        spacerItem = QtWidgets.QSpacerItem(20, 40, QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Expanding)
        self.verticalLayout.addItem(spacerItem)
        self.etiket_lineer = QtWidgets.QLabel(self.verticalLayoutWidget)
        self.etiket_lineer.setStyleSheet("background-color: rgb(211, 215, 207);")
        self.etiket_lineer.setObjectName("etiket_lineer")
        self.verticalLayout.addWidget(self.etiket_lineer)
        self.line_lineer = QtWidgets.QLineEdit(self.verticalLayoutWidget)
        self.line_lineer.setStyleSheet("background-color: rgb(186, 189, 182);")
        self.line_lineer.setReadOnly(True)
        self.line_lineer.setObjectName("line_lineer")
        self.verticalLayout.addWidget(self.line_lineer)
        spacerItem1 = QtWidgets.QSpacerItem(20, 40, QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Expanding)
        self.verticalLayout.addItem(spacerItem1)
        self.verticalLayoutWidget_2 = QtWidgets.QWidget(self.centralwidget)
        self.verticalLayoutWidget_2.setGeometry(QtCore.QRect(210, 480, 160, 81))
        self.verticalLayoutWidget_2.setObjectName("verticalLayoutWidget_2")
        self.verticalLayout_2 = QtWidgets.QVBoxLayout(self.verticalLayoutWidget_2)
        self.verticalLayout_2.setContentsMargins(0, 0, 0, 0)
        self.verticalLayout_2.setObjectName("verticalLayout_2")
        spacerItem2 = QtWidgets.QSpacerItem(20, 40, QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Expanding)
        self.verticalLayout_2.addItem(spacerItem2)
        self.etiket_acisal = QtWidgets.QLabel(self.verticalLayoutWidget_2)
        self.etiket_acisal.setStyleSheet("background-color: rgb(211, 215, 207);")
        self.etiket_acisal.setObjectName("etiket_acisal")
        self.verticalLayout_2.addWidget(self.etiket_acisal)
        self.line_acisal = QtWidgets.QLineEdit(self.verticalLayoutWidget_2)
        self.line_acisal.setStyleSheet("background-color: rgb(186, 189, 182);")
        self.line_acisal.setReadOnly(True)
        self.line_acisal.setObjectName("line_acisal")
        self.verticalLayout_2.addWidget(self.line_acisal)
        spacerItem3 = QtWidgets.QSpacerItem(20, 40, QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Expanding)
        self.verticalLayout_2.addItem(spacerItem3)
        self.label = QtWidgets.QLabel(self.centralwidget)
        self.label.setGeometry(QtCore.QRect(130, 460, 141, 20))
        font = QtGui.QFont()
        font.setFamily("Ubuntu Condensed")
        font.setPointSize(16)
        font.setBold(True)
        font.setWeight(75)
        self.label.setFont(font)
        self.label.setStyleSheet("")
        self.label.setObjectName("label")
        self.verticalLayoutWidget_3 = QtWidgets.QWidget(self.centralwidget)
        self.verticalLayoutWidget_3.setGeometry(QtCore.QRect(30, 360, 160, 81))
        self.verticalLayoutWidget_3.setObjectName("verticalLayoutWidget_3")
        self.verticalLayout_3 = QtWidgets.QVBoxLayout(self.verticalLayoutWidget_3)
        self.verticalLayout_3.setContentsMargins(0, 0, 0, 0)
        self.verticalLayout_3.setObjectName("verticalLayout_3")
        spacerItem4 = QtWidgets.QSpacerItem(20, 40, QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Expanding)
        self.verticalLayout_3.addItem(spacerItem4)
        self.etiket_x = QtWidgets.QLabel(self.verticalLayoutWidget_3)
        self.etiket_x.setStyleSheet("background-color: rgb(211, 215, 207);")
        self.etiket_x.setObjectName("etiket_x")
        self.verticalLayout_3.addWidget(self.etiket_x)
        self.line_x = QtWidgets.QLineEdit(self.verticalLayoutWidget_3)
        self.line_x.setStyleSheet("background-color: rgb(186, 189, 182);")
        self.line_x.setReadOnly(True)
        self.line_x.setObjectName("line_x")
        self.verticalLayout_3.addWidget(self.line_x)
        spacerItem5 = QtWidgets.QSpacerItem(20, 40, QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Expanding)
        self.verticalLayout_3.addItem(spacerItem5)
        self.verticalLayoutWidget_4 = QtWidgets.QWidget(self.centralwidget)
        self.verticalLayoutWidget_4.setGeometry(QtCore.QRect(210, 360, 160, 81))
        self.verticalLayoutWidget_4.setObjectName("verticalLayoutWidget_4")
        self.verticalLayout_4 = QtWidgets.QVBoxLayout(self.verticalLayoutWidget_4)
        self.verticalLayout_4.setContentsMargins(0, 0, 0, 0)
        self.verticalLayout_4.setObjectName("verticalLayout_4")
        spacerItem6 = QtWidgets.QSpacerItem(20, 40, QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Expanding)
        self.verticalLayout_4.addItem(spacerItem6)
        self.etiket_y = QtWidgets.QLabel(self.verticalLayoutWidget_4)
        self.etiket_y.setStyleSheet("background-color: rgb(211, 215, 207);")
        self.etiket_y.setObjectName("etiket_y")
        self.verticalLayout_4.addWidget(self.etiket_y)
        self.line_y = QtWidgets.QLineEdit(self.verticalLayoutWidget_4)
        self.line_y.setStyleSheet("background-color: rgb(186, 189, 182);")
        self.line_y.setReadOnly(True)
        self.line_y.setObjectName("line_y")
        self.verticalLayout_4.addWidget(self.line_y)
        spacerItem7 = QtWidgets.QSpacerItem(20, 40, QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Expanding)
        self.verticalLayout_4.addItem(spacerItem7)
        self.label_2 = QtWidgets.QLabel(self.centralwidget)
        self.label_2.setGeometry(QtCore.QRect(110, 340, 171, 20))
        font = QtGui.QFont()
        font.setFamily("Ubuntu Condensed")
        font.setPointSize(16)
        font.setBold(True)
        font.setWeight(75)
        self.label_2.setFont(font)
        self.label_2.setStyleSheet("")
        self.label_2.setObjectName("label_2")
        self.verticalLayoutWidget_5 = QtWidgets.QWidget(self.centralwidget)
        self.verticalLayoutWidget_5.setGeometry(QtCore.QRect(210, 250, 160, 80))
        self.verticalLayoutWidget_5.setObjectName("verticalLayoutWidget_5")
        self.verticalLayout_5 = QtWidgets.QVBoxLayout(self.verticalLayoutWidget_5)
        self.verticalLayout_5.setContentsMargins(0, 0, 0, 0)
        self.verticalLayout_5.setObjectName("verticalLayout_5")
        spacerItem8 = QtWidgets.QSpacerItem(20, 40, QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Expanding)
        self.verticalLayout_5.addItem(spacerItem8)
        self.label_3 = QtWidgets.QLabel(self.verticalLayoutWidget_5)
        font = QtGui.QFont()
        font.setFamily("Ubuntu Condensed")
        font.setPointSize(14)
        font.setBold(True)
        font.setWeight(75)
        self.label_3.setFont(font)
        self.label_3.setObjectName("label_3")
        self.verticalLayout_5.addWidget(self.label_3)
        self.progressBar = QtWidgets.QProgressBar(self.verticalLayoutWidget_5)
        self.progressBar.setStyleSheet("background-color: rgb(186, 189, 182);")
        self.progressBar.setProperty("value", 61)
        self.progressBar.setObjectName("progressBar")
        self.verticalLayout_5.addWidget(self.progressBar)
        spacerItem9 = QtWidgets.QSpacerItem(20, 40, QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Expanding)
        self.verticalLayout_5.addItem(spacerItem9)
        self.gridLayoutWidget = QtWidgets.QWidget(self.centralwidget)
        self.gridLayoutWidget.setGeometry(QtCore.QRect(600, 470, 341, 171))
        self.gridLayoutWidget.setObjectName("gridLayoutWidget")
        self.gridLayout = QtWidgets.QGridLayout(self.gridLayoutWidget)
        self.gridLayout.setContentsMargins(0, 0, 0, 0)
        self.gridLayout.setObjectName("gridLayout")
        self.buton_sag = QtWidgets.QPushButton(self.gridLayoutWidget)
        self.buton_sag.setObjectName("buton_sag")
        self.gridLayout.addWidget(self.buton_sag, 1, 1, 1, 1)
        self.buton_ileri = QtWidgets.QPushButton(self.gridLayoutWidget)
        self.buton_ileri.setObjectName("buton_ileri")
        self.gridLayout.addWidget(self.buton_ileri, 0, 0, 1, 2)
        self.buton_geri = QtWidgets.QPushButton(self.gridLayoutWidget)
        self.buton_geri.setObjectName("buton_geri")
        self.gridLayout.addWidget(self.buton_geri, 2, 0, 1, 2)
        self.buton_sol = QtWidgets.QPushButton(self.gridLayoutWidget)
        self.buton_sol.setObjectName("buton_sol")
        self.gridLayout.addWidget(self.buton_sol, 1, 0, 1, 1)
        self.etiket_kontrol = QtWidgets.QLabel(self.centralwidget)
        self.etiket_kontrol.setGeometry(QtCore.QRect(600, 450, 221, 20))
        font = QtGui.QFont()
        font.setFamily("Ubuntu Condensed")
        font.setPointSize(14)
        font.setBold(True)
        font.setWeight(75)
        self.etiket_kontrol.setFont(font)
        self.etiket_kontrol.setObjectName("etiket_kontrol")
        creatiny.setCentralWidget(self.centralwidget)
        self.statusbar = QtWidgets.QStatusBar(creatiny)
        self.statusbar.setObjectName("statusbar")
        creatiny.setStatusBar(self.statusbar)

        self.retranslateUi(creatiny)
        QtCore.QMetaObject.connectSlotsByName(creatiny)
       
       

    def retranslateUi(self, creatiny):
        _translate = QtCore.QCoreApplication.translate
        creatiny.setWindowTitle(_translate("creatiny", "MainWindow"))
        self.buton_dur.setWhatsThis(_translate("creatiny", "<html><head/><body><p><br/></p></body></html>"))
        self.buton_dur.setText(_translate("creatiny", "DUR"))
        self.etiket_lineer.setText(_translate("creatiny", "       Lineer Hız (m/s)"))
        self.etiket_acisal.setText(_translate("creatiny", "       Açısal Hız (m/s)"))
        self.label.setText(_translate("creatiny", "  HIZ GÖSTERGESİ"))
        self.etiket_x.setText(_translate("creatiny", "         KONUM X (m)"))
        self.etiket_y.setText(_translate("creatiny", "         KONUM Y (m)"))
        self.label_2.setText(_translate("creatiny", " KONUM GÖSTERGESİ"))
        self.label_3.setText(_translate("creatiny", "ŞARJ DURUM"))
        self.buton_sag.setText(_translate("creatiny", "SAĞ"))
        self.buton_ileri.setText(_translate("creatiny", "İLERİ"))
        self.buton_geri.setText(_translate("creatiny", "GERİ"))
        self.buton_sol.setText(_translate("creatiny", "SOL"))
        self.etiket_kontrol.setText(_translate("creatiny", "KONTROL PANELİ"))



        rospy.init_node("creatiny")
        self.pub = rospy.Publisher("cmd_vel",Twist,queue_size=10)
        self.hiz_mesaji = Twist()
        rospy.Subscriber("odom",Odometry,self.odomCallback)
        
        self.buton_dur.clicked.connect(self.robotDur)
        self.buton_ileri.clicked.connect(self.ileriGit)
        self.buton_geri.clicked.connect(self.geriGit)
        self.buton_sag.clicked.connect(self.sagaDon)
        self.buton_sol.clicked.connect(self.solaDon)
        
        
        self.line_acisal.setText(str(0.0))
        self.line_lineer.setText(str(0.0))
        self.line_x.setText(str(0.0))
        self.line_y.setText(str(0.0))
        
        
    def odomCallback(self,mesaj):
         self.line_x.setText(str(mesaj.pose.pose.position.x,4))
         self.line_y.setText(str(mesaj.pose.pose.position.y,4))
         
         
    def robotDur(self):
        self.hiz_mesaji.linear.x= 0.0
        self.hiz_mesaji.angular.z= 0.0
        self.pub.publish(self.hiz_mesaji)
        self.line_lineer.setText(str(self.hiz_mesaji.linear.x))
        self.line_acisal.setText(str(self.hiz_mesaji.angular.z))
        
        
    def ileriGit(self):
        self.hiz_mesaji.linear.x= 1.0
        self.hiz_mesaji.angular.z= 0.0
        self.pub.publish(self.hiz_mesaji)
        self.line_lineer.setText(str(self.hiz_mesaji.linear.x))
        self.line_acisal.setText(str(self.hiz_mesaji.angular.z))  
        
        
    def geriGit(self):
        self.hiz_mesaji.linear.x= -1.0
        self.hiz_mesaji.angular.z= 0.0
        self.pub.publish(self.hiz_mesaji)
        self.line_lineer.setText(str(self.hiz_mesaji.linear.x))
        self.line_acisal.setText(str(self.hiz_mesaji.angular.z))
        
    def solaDon(self):
        self.hiz_mesaji.linear.x= 0.0
        self.hiz_mesaji.angular.z= -0.5
        self.pub.publish(self.hiz_mesaji)
        self.line_lineer.setText(str(self.hiz_mesaji.linear.x))
        self.line_acisal.setText(str(self.hiz_mesaji.angular.z))
        
    def sagaDon(self):
        self.hiz_mesaji.linear.x= 0.0
        self.hiz_mesaji.angular.z= 0.5
        self.pub.publish(self.hiz_mesaji)
        self.line_lineer.setText(str(self.hiz_mesaji.linear.x))
        self.line_acisal.setText(str(self.hiz_mesaji.angular.z))
        
        

        
        

if _name_ == "_main_":
    import sys
    app = QtWidgets.QApplication(sys.argv)
    creatiny = QtWidgets.QMainWindow()
    ui = Ui_creatiny()
    ui.setupUi(creatiny)
    creatiny.show()
    sys.exit(app.exec_())
