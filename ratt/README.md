{
 "cells": [
  {
   "attachments": {},
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Init GPIO\n",
    "## Jag antar att det går att rita någon slags graf över HALL-sensorerna\n",
    "\n",
    "pip install jupyterlab\n",
    "pip install curcuitpython\n",
    "\n",
    "Detta ska kunna köras på en MCU med hög frekvens. Testa först och fungera sist.\n",
    "Planen är att bygga en ESC till en borstlös likströmsmotor med delar och motor ifrån en hooverboard. \n",
    "Taget från hooverboard är två st BLDC-motorer med HALL-sensorer, tillräckligt många tåliga MOSFETs, 2 st ICs IR2136S. \n",
    "\n",
    "Målet är en enkel och bra drivkrets som kan konkurera med vad som används idag till egenbyggda rattar för simulatorer. Ofta använs AC-servomotorer och \n",
    "tillhörande dyra drivkretsar. Min tanke är att med lätttillgängliga medel göra ett \"gratis\" hemmabygge som är minst lika bra. Min tanke är eftersom hastigheten är låg så är latency och kvaliten på motordriften viktigare än maximalt moment. Dessutom har jag nästan bara sett att drivkretsar som är avsedda till andra ändamål användas. De motorer som finns i hooverboardhjul bör vara minst lika kompetenta som en industriell servomotor med rätt mjukvara och jag är säker på att det går att lista ut ett sätt att klara sig utan encoder/vinkelsensor. \n",
    "\n",
    "Detta projektet började på orginal flashad SMT32 som fanns i hooverboarden, vilken är helt optimal till ändamålet, men fortsätter på en raspberry så länge. \n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "language_info": {
   "name": "python"
  },
  "orig_nbformat": 4
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
