#See https://aka.ms/containerfastmode to understand how Visual Studio uses this Dockerfile to build your images for faster debugging.

FROM mcr.microsoft.com/dotnet/core/aspnet:3.1 AS base

RUN mkdir -p /usr/local/testcicd

WORKDIR /usr/local/testcicd

VOLUME "/usr/local/testcicd"

COPY . /usr/local/testcicd

EXPOSE 23997

ENV ASPNETCORE_URLS http://+:23997