# SPDX-FileCopyrightText: 2023 The Pion community <https://pion.ly>
# SPDX-License-Identifier: MIT

FROM golang:1.21

RUN go install github.com/pyu1538/pion_webrtc/v4/examples/pion-to-pion/answer@latest

CMD ["answer"]

EXPOSE 50000
