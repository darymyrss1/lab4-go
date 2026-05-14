package main

import (
        "fmt"
	    "log"

	    "github.com/skip2/go-qrcode"
)

func main() {
	data := "https://google.com"
    fileName := "qrcode.png"

    fmt.Println("Генерация QR-кода запущена...")

    err := qrcode.WriteFile(data, qrcode.Medium, 512, fileName)
	if err != nil {
		log.Fatal("Критическая ошибка: ", err)
	}
    fmt.Printf("Готово! QR-код для %s сохранен как %s\n", url, fileName)
}
