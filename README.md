#!/usr/bin/python
# -*- coding: utf-8 -*-


class SoftwareEngineerStudent:

    def __init__(self):
        self.name = "Utku Buğra Yılmaz"
        self.role = "Software Engineer Student"
        self.language_spoken = ["tr_TR", "en_US", "de_DE"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting!")


me = SoftwareEngineerStudent()
me.say_hi()


#!/usr/bin/python
# -*- coding: utf-8 -*-


class SoftwareEngineer:

    def __init__(self):
        self.name = "Zhenye Na"
        self.role = "Software Engineer"
        self.language_spoken = ["zh_CN", "en_US"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")


me = SoftwareEngineer()
me.say_hi()
