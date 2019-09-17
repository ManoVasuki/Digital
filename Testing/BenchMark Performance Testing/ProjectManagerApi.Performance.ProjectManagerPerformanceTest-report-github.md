``` ini

BenchmarkDotNet=v0.11.0, OS=Windows 10.0.17134.1006 (1803/April2018Update/Redstone4), VM=Hyper-V
Intel Xeon Gold 6140 CPU 2.30GHz, 1 CPU, 3 logical and 3 physical cores
.NET Core SDK=2.1.509
  [Host]     : .NET Core 2.1.13 (CoreCLR 4.6.28008.01, CoreFX 4.6.28008.01), 64bit RyuJIT
  DefaultJob : .NET Core 2.1.13 (CoreCLR 4.6.28008.01, CoreFX 4.6.28008.01), 64bit RyuJIT


```
|           Method |     Mean |     Error |   StdDev |
|----------------- |---------:|----------:|---------:|
| InvokeController | 4.196 ms | 0.3894 ms | 1.124 ms |
