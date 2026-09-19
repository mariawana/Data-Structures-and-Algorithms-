#include <iostream>
#include <chrono>

using namespace std;

int main()
{
    const long long N = 1000000;
    long long count = 0;

    auto start = chrono::high_resolution_clock::now();

    for (long long i = 0; i < N; i++)
    {
        count++;
    }

    auto end = chrono::high_resolution_clock::now();

    chrono::duration<double, milli> duration = end - start;

    cout << "=== Loop Benchmark Result ===" << endl;
    cout << "Number of iterations: " << N << endl;
    cout << "Final count: " << count << endl;
    cout << "Execution Time: " << duration.count() << " ms" << endl;

    return 0;
}
