## Pcap loss analyzer

Инструмент для поиска потерь пакетов по трассе обменов на транспортном уровне.

Отображает заголовки пакетов в ключ, пакеты с одинаковым ключом из 
списков отправленных и полученных пакетов объединяются в группы.

В рамках группы с общим ключом сравнивается хэшированное тело пакета,
на основе сравнения определяются пакеты, которые нет в одной из групп.